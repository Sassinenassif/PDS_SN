# README: Assignment 5 



## Libraries Used:

The following Python libraries were employed to accomplish the tasks:


* **'glob':** Used for finding all files matching a specific pattern in a directory.  This was essential for locating all annotation files (`.txt`) within a specified folder.  `glob.glob()` returns a list of file paths.

* **'os':** Provides functions for interacting with the operating system, specifically used here for extracting the file name from a full file path (`os.path.basename()`).

* **'re' (regular expressions):**  Used for pattern matching in file names.  A regular expression was defined to extract year, month, and other relevant information from annotation filenames. `re.match()` was used to check if each filename matched the specified pattern.

* **'datetime':**  Provides classes for working with dates and times.  Used to parse the date information extracted from the filenames into `datetime` objects, enabling date-based operations (e.g., sorting).

* **'numpy' (NumPy):**  While not strictly necessary for this particular assignment, NumPy is a powerful library for numerical computation. It could potentially be useful for other data analysis tasks or if the assignment was expanded to involve more numerical data processing.

* **'json':**  Used for encoding and decoding JSON data. This library was employed to save and load a dictionary representing the annotations organized by month in JSON format, offering a human-readable and easily shareable way to store the processed results.

* **'pickle':**  Used for serialization and deserialization of Python objects.  This library enables saving and loading the annotation dictionary in a binary format (pickle), providing efficient storage and retrieval of the processed data.
