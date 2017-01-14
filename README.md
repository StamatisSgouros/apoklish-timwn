# apoklish-timwn
 παίρνει σαν είσοδο μία λίστα και επιστρέφει την τυπική απόκλιση των τιμών χωρίς να χρησιμοποιεί τις δύο μεγαλύτερες και δύο μικρότερες τιμές
print "dwse times"
lista=raw_input()
newlista=lista.split( )
for i in range (len(newlista)):
	newlista[i]=float(newlista[i])
newlista.sort()
apoklish=newlista[-3]-newlista[2]
print apoklish	
