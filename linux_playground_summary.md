mkdir day1_practice        # Create project folder
cd day1_practice

# Create and write to files
echo "First file content" > fileA.txt
echo "Second file content" > fileB.txt

# Combine two files into one
cat fileA.txt fileB.txt > combined.txt

# View combined file
cat combined.txt

# Edit file manually (you used nano)
nano fileA.txt

# Remove a file
rm fileB.txt

# Git workflow
git add .
git commit -m "Day 1 practice completed"
git push

# Create, copy, move, and delete files
touch file1.txt file2.txt
echo "This is content inside file1" > file1.txt
echo "Extra line in file2" >> file2.txt
cp file1.txt file3.txt
mv file2.txt file_2.0.txt
rm file3.txt

# Create and move file to folder
mkdir demo_folder
mv file1.txt demo_folder/
cd demo_folder
ls
cd ..
rm -r demo_folder



X

