# HI7090
import csv

with open("test.txt", "r") as f:
    reader = csv.reader(f, delimiter="\t")
    for i, line in enumerate(reader):
        print(line)
