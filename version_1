# Project title: sms conversion
# Author: Benjamin Nolan
# Date completed: 04/12/2018
# Desc: take something like LOL and translate into Laugh Out Loud using lists

# ask for input
sms_text = input('Enter SMS abbreviation: ')

#for debugging
#sms_text = 'foo'

def sms_conversion(sms_text):
    
    # set output variable
    conversion = 'Undefined'

    # define sms_list short and full
    sms_flist = ['Laugh Out Loud','Oh My God','Be Right Back','Do Not Disturb']
    sms_slist = ['LOL','OMG','BRB','DND']

    # convert given abbrev to upper case for matching
    new_text = sms_text.upper() 

    #need to iterate through each element in (sms short list) and look for new_text match
    for elem in sms_slist:
        # need an index position to match up
        pos = sms_slist.index(elem)
        # if elem is equal to new_text, set conversion as the position of index in (sms full list)
        if elem == new_text:
            conversion = sms_flist[pos]

    # return conversion
    return conversion

# call function
get_conversion = sms_conversion(sms_text)

# output value
print(get_conversion)
