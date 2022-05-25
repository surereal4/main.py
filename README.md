# Check if two words are anagrams 
# Example:
# find_anagrams("hello", "check") --> False
# find_anagrams("below", "elbow") --> True


def find_anagram(word, anagram):
    # [assignment] Add your code here
    string1 = input("Enter the first word\n")
    string2 = input("Enter the second word\n")
    if(sorted(string1) == sorted(string2)):
        print("The two strings are anagram")
    else:
        print("The two strings are not anagram")
find_anagram("coronavirus", "carnivorous")
