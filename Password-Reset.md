Assuming you have GRUB as your [[bootloader]]:

1. Turn off the machine.

2. Power on.

3. Hold down `SHIFT` after [[POST]].

4. ***Highlight*** the option that says `recovery`.

5. Press `e` for edit.

6. Move cursor to the line that says `linux` on the left.

7. Press `END`.

8. Locate (with your eyes) the part of the line that says `ro`.

9. Delete everything from the end of the line to the `r` in `ro`.

    * It should just say `r` at the end of the line.

10. After the `r` add `w init=/bin/bash`

    * So it is `rw init=/bin/bash`.

11. Press `F10` to start the computer.

12. Wait until the [[shell]] pops up with `(none) #`.

    * Sometimes the keyboard just stops working :/
    
    * Start over from Step 1 until it decides to work.

13. Find your username with `tail /etc/passwd`.

    * If it's not displayed check the whole file with `cat /etc/passwd`.

14. Change your password with `passwd <username>`.

    * When you type in your new password no characters will show on the screen.

    * It will ask you to type in your password twice to confirm.

    * `password updated successfully` is a good sign.

    * Recheck your username if there are issues.

15. Type the command `sync` and hit enter.

16. `CTRL` + `ALT` + `DEL` to reboot.

17. Select the correct boot option at the GRUB menu.

    * It will stop and wait for you to select an option.

18. Log in with your new fancy password.

19. Remember your new password.