CHALLENGE NAME: Ancient Encodings
DESCRIPTION: Your initialization sequence requires loading various programs to gain the necessary knowledge and skills for your journey. Your first task is to learn the ancient encodings used by the aliens in their communication.


</br></br></br>


Lets start by reading the encryption code ...

![Alt text](./encrypt.png "encrypt")

It is very simple: encode by converting it to base64, then to hex. We can reverse these steps with the encrypted message.

I used <a herf="https://gchq.github.io/CyberChef/">CyberChef</a> to do that ... 

![Alt text](./solved.png "solved")

Here is the flag :)

```HTB{1n_y0ur_j0urn3y_y0u_wi1l_se3_th15_enc0d1ngs_ev3rywher3}```
