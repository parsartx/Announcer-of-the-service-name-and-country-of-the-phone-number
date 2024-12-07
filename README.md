
from phonenumbers import parse
from phonenumbers import geocoder
from phonenumbers import carrier

Phonenuber = input ("Enter The phonenumber : ")

number = parse(Phonenuber)
 
print(geocoder.description_for_number(number,'en'))
print(carrier.name_for_number(number, 'en'))






off = input ("Press any key to close")
