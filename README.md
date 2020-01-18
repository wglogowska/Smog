#Sprawdzenie ilosci PM 2,5 w powietrzu

MAX_PM=25

smog=float(input("Podaj w mg zawartosc PM2.5 w powietrzu: "))

while smog > MAX_PM:
    print('Jeżeli możesz zostań w domu.')
    print('Zbyt duże zanieszczyszenie powietrza.')
smog=float(input("Podaj w mg zawartosc PM2.5 w powietrzu: "))    
   
print('Swieze powietrze')
