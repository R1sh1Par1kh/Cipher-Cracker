# main.py

password = "tavaenryvahwribyv"

rstring = ""

'''
(start, end, counter)
'''
for i in range(len(password)-1,-1,-1):
  rstring += password[i]
print(rstring)

for i in range(1,27,1):
  decryption = ""
  for letter in rstring:
    num = ord(letter)- int(i)
    while num < 97:
      num += 26
    decryption += chr(num)
    
    
  print(decryption)
