# computer-organization-billing-system-circ
AIM: BILLING SYSTEM
Procedure:
We have created a CIRC file which is used to calculate the total price of items purchased and find the total cost. The price of items are already stored in the Memory and the address signifies the item Id. The Item Id and the number of quantity will be selected by the user. After two clock pulses, we will get the total calculated price, which will be stored in a register and then again if user selects another item Id and quantity, it will give the total sum of previous output and the current amount. Also the total number of products purchased are displayed.

Concepts used:
For addition purpose we have used the concept of register addition and for multiplication purpose we have used the concept of array multiplier. Also for display purpose 7 segment display method is used. For storing price value a 4 way set associative cache memory. The cache memory is made using 8 registers for index representation and 8 registers each of 24 bits. Each index register is used for checking the index each having 4 tags. The length of data is 4 bits. There is a key register of 5 bits and input address register of 5 bits, of which first 3 bits are index bits and 2 other bits are tag bits. There is a priority encoder used for selection the index and tag we selected and the multiplexer for selecting data of selected index and tag.

MADE BY: NISHITA SHAH (15BCE108)
MEERA SUTHAR (15BCE120)
