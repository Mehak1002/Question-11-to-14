# Question-11-to-14

#QUESTION 11
                            
def prime(n):
    if n==1:
        return False
    for i in range(2,n):
        if n%i==0:
            return False
            break
    else:
        return True
    return prime(n)
def main():
    n=int(input('enter no.:'))
    result=prime(n)
    if result==True:
        print(n,'is a prime no.')
    else:
        print(n,'is not a prime no.')
if __name__=='__main__':
    main()

                           
QUESTION 12
                            
def main():
    a=input('enter a string:')
    b=a[-1::-1]
    if(a==b):
        print('palindrome string')
    else:
        print('not palindrome')
if __name__=='__main__':
    main()
    
QUESTION 13

def pallindrome():
    str = input("Enter a string to check whether it's a palindrome or not  :  ")
    str = str.lower()
    length = len(str)-1
    for i in range(0,length):
        if  str[i] ==str[length]:
            length-=1
            print("string is a pallindrome :) ")
        else:
            print("string is not a pallindrome :( ")
while True:
        
    pallindrome()
                            
 QUESTION 14
                            
 def main():
    text = input('Enter a sentence:')
    freq = {}
    for i in text:
        if i in freq:
            freq[i] += 1
        else:
            freq[i] = 1
    print("Frequency of each letter are as follows:", freq)
if __name__=='__main__':
    main()
