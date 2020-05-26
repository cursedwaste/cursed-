missions = ["read", "practice", "learn", "pray"]
for mission in missions:
  print (mission)
  

sentence = "python is amazing"
for letter in sentence :
  print (letter)
 
# str.split(sep=None, maxsplit=-1)

# code 1
m = "split method is very useful"
arr = m.split(' ')
print (arr[0])
print (arr[1])
print (arr[2])
print (arr[3])
print (arr[4])

# code 2
m = "split method is very useful"
arr = m.split(' ')
for element in arr :
  print (element)

# str.splitlines([keepends])

# code 1
m = "this is first line. \n this is second line. \n this is third line."
arr = m.splitlines()
print (arr[0])
print (arr[1])
print (arr[2])

# code 2
m = "this is first line. \n this is second line. \n this is third line."
arr = m.splitlines()
for element in arr :
  print (element )
  
m = "we are legions "
print (m)

# str.replace(old, new[, count])
m = "java is easy to learn. anyone can learn java."
print (m)
print (m.replace('java','python'))

# static str.maketran(x,[,y[,z]])
# code 1
m = "youcef.com"
dictionary = str.maketrans('a','-')
print (m)
print (m.translate(dictionary))
# code 2
m = "youcef.com"
dictionary = str.maketrans('am','-*')
print (m)
print (m.translate(dictionary))
# code 3
m = "youcef.com"
dictionary = str.maketrans('a','-','m')
print (m)
print (m.translate(dictionary))
# code 4
m ="youcef.com"
dictionary = ({
  'h':'xyz',
  'a':'444',
  '-':''
})
print (m)
print (m.translate(dictionary))
