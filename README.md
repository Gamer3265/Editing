# Editing
A place to upload work and change or up data it
def isSorted(lst):
    
    if len(lst) <= 1:
        return True
    for i in range(len(lst)-1):
        if lst[i] > lst[i+1]:
            return False
    
    return True

def main():
  lyst=[]
  print(isSorted(lyst))
  lyst=[7]
  print(isSorted(lyst))
  lyst=list(range(4))
  print(isSorted(lyst))
  lyst[2]=9
  print(isSorted(lyst))
main()
