# ALLlower-to-uppercase-and-viceversa-with-Python
def swap_case(s):
    new_string=""
    for i in s:
        if(i.islower()):
            new_string+=i.upper()
        elif(i.isupper()):
            new_string+=i.lower()
        else:
            new_string+=i
            
    return new_string      
    

if __name__ == '__main__':
    s = input()
    result = swap_case(s)
    print(result)
