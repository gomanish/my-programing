def anagram(s,t):
    s=s.replace(' ','').lower()
    t=t.replace(' ','').lower()
    print(s,t)
    if len(s)!=len(t):
        return False
    counter={}
    for letter in s:
        if letter in counter:
            counter[letter]+=1
        else:
            counter[letter]=1
    for letter in t:
        if letter in counter:
            counter[letter]-=1
        else:
            return False
    for k in counter:
        if counter[k]!=0:
            return False
    return True
if __name__ == '__main__':
	s=input('Enter first string ')
	t=input('Enter second string ')
	if anagram(s,t):
		print('first string and second string are anagram of each other')
	else:
		print('first string and second string are not anagram')

