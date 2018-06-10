# ICC20181
#Se busca hallar el volumen de un prisma
def vol(l,a,h):
    return(l*a*h)
class color:
   PURPLE = '\033[95m'
   CYAN = '\033[96m'
   DARKCYAN = '\033[36m'
   BLUE = '\033[94m'
   GREEN = '\033[92m'
   YELLOW = '\033[93m'
   RED = '\033[91m'
   BOLD = '\033[1m'
   UNDERLINE = '\033[4m'
   END = '\033[0m'
   print(color.BOLD+"BIENVENIDO A TU PROGRAMA".center(100," ")+color.END)
   print(color.BOLD+color.UNDERLINE+"Área de un prisma de base rectangular".center(100," ")+color.END)
m=int(input(color.RED+"Ingresa el largo de la base del prisma: "+color.END))
n=int(input(color.RED+"Ingresa el ancho de la base: "+color.END))
o=int(input(color.RED+"Ingresa la altura del prisma: "+color.END))
print(color.BLUE+color.UNDERLINE+"El volúmen es:"+color.END,vol(m,n,o))
print(color.BOLD+color.UNDERLINE+"GRACIAS POR TU PREFERENCIA".center(100," ")+color.END)
