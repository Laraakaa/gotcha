# Gotcha!
Make users aware of the danger of random USB sticks.

This is a project for the USB Rubber Ducky.

## TL; DR
Once you connect the Rubber Ducky to the PC, it opens up the default browser with the URL "https://gotcha.lars.ninja#{computername}", where {computername} is the name of the windows account the user is currently logged onto. Please note that {computername} is not accessible from the frontend, because it is a fragment. More about that here: https://stackoverflow.com/a/940923/7658355

## Technologies:
- **Hardware**: Rubber Ducky by Hak5: https://www.hak5.org/gear/usb-rubber-ducky/
- **Hosting**: GitHub Pages: https://pages.github.com/
- **Design**: Custom, inspired by https://codepen.io/saransh/pen/BKJun
