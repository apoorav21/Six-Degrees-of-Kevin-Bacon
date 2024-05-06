The distribution code contains two sets of CSV data files: one set in the large directory and one set in the small directory.
Each contains files with the same names, and the same structure, but small is a much smaller dataset for ease of testing and experimentation.
The main function in this program first loads data into memory (the directory from which the data is loaded can be specified by a command-line argument).
Then, the function prompts the user to type in two names.
The person_id_for_name function retrieves the id for any person (and handles prompting the user to clarify, in the event that multiple people have the same name).
The function then calls the shortest_path function to compute the shortest path between the two people, and prints out the path.
