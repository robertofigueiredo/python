from random import randint 

def ordenada(l):
    n = len(l)
    for i in range (0,n-1):
        if l[i] > l[i+1]:
            return False
    return True

def aleatoria (n):
    l = []
    for i in range(n):
        l.append(randint(10,99))
    return l

def teste (l,i,j): # teste (Lista,oq se quer mudar, pra onde mudar)
    x = l[i]
    l[i] = l[j]
    l[j] = x
    
def seleciona (l,n):
    m = 0
    for i in range (1,n):
        if l[i] > l[m]:
            m = i
    return m

def selection_sort(l):
    n = len(l)
    for i in range(n,1,-1):
        m = seleciona (l,i)
        teste (l,m,i-1)

def preenche ():
    l = []
    for i in range (5):
        l.append(int(input("Valor;")))
    return l
