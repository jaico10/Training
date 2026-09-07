Input: digits = "23"
Output: ["ad","ae","af","bd","be","bf","cd","ce","cf"]
Example 2:
 
Input: digits = ""
Output: []
Example 3:
 
Input: digits = "2"
Output: ["a","b","c"]E






d = {2: "abc",3: "def",4: "ghi",5: "jkl",6: "mno",7: "pqrs",8: "tuv",9: "wxyz"}
t = input()
l = []

if t == "":
    print([])
else:
    l = list(d[int(t[0])])

    for i in range(1, len(t)):
        st = d[int(t[i])]
        new = []

        for x in l:
            for y in st:
                new.append(x + y)

        l = new

    print(l)
