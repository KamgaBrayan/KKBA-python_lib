___________________________________________________________________________________________

This is a comprehensive guide to understand the functioning of each function in this module.

Each of these functions may be used with respect to the directives given bellow.

In the following table, you will have the name of the function, its parameters and the output.
____________________________________________________________________________________________

function                parameters                            output

get_divisors            Integer n                      List of divisors of n
isprime                 Integer n                      True if n is prime and vice versa
primes_list             Integer interval (min,max)     List of prime numbers in interval
prime_divisors          Integer n                      List of prime divisors of n
isperfect               Integer n                      True if n is a perfect number
ispower_another_number  Couple (n,p)                   True if there exist x such that n = x^p  
perfect_numbers_list    integer interval (min,max)     List of perfect numbers
mean_of_list            List                           Mean of elements in the list
harmonic_mean           List                           Mean if 1/elements in list
isBigPrime              Integer n                      True if n is prime
Encrypt_Cesar           (Word(capital letters) , key)  Ecncrypted Word
Decrypt_Cesar           (encrypted word , key)         Clear message
EncryptVig              (Word(capital letters) , key)  Encrypted Word
DecryptVig              (encrypted word , key)         Clear Message
fibonacci               Integer n                      Return the n-th term of fibronacci series
variance                List                           Returns the variance of a set of data
standard_deviation      List                           Returns standard deviation of elements
merge_map               Two maps (dict1 and dict2)     Merge two maps
merge_map_for           Same function as above but written differently
decimal_to_binary       Integer n                      n in base 2
binary_to_decimal       Binary number                  Base 10
decimal_to_hexadecimal  Integer n                      n in base 16
hexadecimal_to_decimal  Hexadecimal number             Base 10
vector_add              Two vectors                    Sum of two vectors
generate_random_matrix  (M rows, N columns)            A matrix of order MxN
show_matrix             matrix                         Prints the matrix completely
area_circle             Radius                         Area of circle with radius 
circumference_circle    Radius                          //
area_triangle           (base , height)                 //
perimeter_triangle      (side1, side2, side3)          Perimeter (Sum of all three sides)
unique_elements         Liste                          Returns True if there is only one occurence for each elements
trimorphic              Integer n                      True if last digits of n³ equals n
natural_to_roman        Natural number n               Writes n in roman numerals
roman_to_natural        Roman numerals                 Writes it as a natural number
gcd                     (x , y)                        Greatest common divisor between x and y


The following functions need proper explanation inorder to understand their functioning
_______________________________________________________________________________________

Geometric mean : This code defines a function called geometrique that calculates the geometric mean of a list of numbers. It multiplies all the numbers in the list together and then raises the product to the power of the reciprocal of the list length. The result is the geometric mean.

Quadratic mean : This code calculates the root mean square of the elements in a given list. It squares each element, adds them up, divides by the length of the list, and then takes the square root of the result.

