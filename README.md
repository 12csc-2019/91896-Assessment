# 91896-Assessment
Please include all of your work towards 91896 in this folder.

### Specifications

Your character creation section must meet the following specifications:

1.  Allow the user to select from 5 different types of clothing; this should
    include;

    1.  Buttons to scroll to the previous and next item of clothing

    2.  Text displaying the current selection

    3.  Information about each item of clothing needs to be stored in a table

        1.  Note: This same list will be used to load the images for items of
            clothing, so spelling and case are important

2.  A way for the user to select the characters gender.

3.  Have an area where the user can enter the following text;

    1.  Characters name.

        1.  This should be between 3 and 15 characters inclusive.

        2.  (optional) Should not start with any numbers or special characters.

            1.  <https://docs.coronalabs.com/guide/data/luaString/index.html>

        3.  Display appropriate feedback if the user enters an invalid name.

    2.  Character’s strength

        1.  CSC Gaming has requested this be between 1 and 100 inclusive

        2.  Display appropriate feedback if the user enters an invalid strength.

4.  Have a button that the user will press that will proceed to the next
    section.

5.  When that button is pressed, the following will be displayed.

    1.  A title for the character screen (your choice)

    2.  The characters name.

    3.  Change the characters head depending on the gender of the final
        character.

    4.  The character wearing the appropriate clothing.

        1.  You will need to place these all on the screen in the correct
            location

    5.  The characters hit points displayed in an appropriate way. This should
        be calculated using the following formula;

        1.  Hitpoints = strength \* 10 / 1.3
