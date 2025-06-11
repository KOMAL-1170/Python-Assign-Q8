# Python-Assign-Q8
# Define the list
L = ["One", "Two", "Three", "Four", "Five"]

# Open a file for writing
with open("length_output.txt", "w") as file:
    for word in L:
        file.write(f"{word}, {len(word)}\n")

print("Lengths written to 'length_output.txt' successfully.")

