class Solution:
    def intToRoman(self, num: int) -> str:
        
        units = {0: '',1: 'I',2: 'II',3: 'III',4: 'IV',5: 'V',6: 'VI',7: 'VII',8: 'VIII',9: 'IX'}
        tens = {0: '',10: 'X', 20: 'XX', 30: 'XXX', 40: 'XL', 50: 'L', 60: 'LX', 70: 'LXX', 80: 'LXXX', 90: 'XC'}
        hundreds = {0: '',100: 'C', 200: 'CC', 300: 'CCC', 400: 'CD', 500: 'D', 600: 'DC', 700: 'DCC', 800: 'DCCC', 900: 'CM'}
        thousands = {0: '',1000: 'M', 2000: 'MM', 3000: 'MMM'}

        units_of_num = num%10 
        tens_of_num = num%100 - num%10
        hunds_of_num = num%1000 - num%100
        thous_of_num = num - num%1000

        Number = str(thousands[thous_of_num] + hundreds[hunds_of_num] + tens[tens_of_num] + units[units_of_num])

        return Number
