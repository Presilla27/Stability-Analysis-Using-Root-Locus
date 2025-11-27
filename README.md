# Stability Analysis using Root Locus
## Aim:
To analyse the stability of the system having open loop transfer function, G(S)=K/(S(S+5)(S+10)) using root locus and verify it using MATLAB. 
## Apparatus Required:
Computer with MATLAB software

## Theory:
![WhatsApp Image 2025-11-27 at 21 15 05_90d75637](https://github.com/user-attachments/assets/3a97bc7c-0147-4163-8355-19c9e7cd9cef)
![WhatsApp Image 2025-11-27 at 21 15 05_9a0c9454](https://github.com/user-attachments/assets/cbfae69a-4451-4cb1-a14e-32f6471b6b25)
![WhatsApp Image 2025-11-27 at 21 15 06_5990af03](https://github.com/user-attachments/assets/fa9facf0-ee24-47c5-a85f-3906b813f325)
![WhatsApp Image 2025-11-27 at 21 15 06_ac60f751](https://github.com/user-attachments/assets/82ec1f7e-1fcd-4d6e-83ab-c38a7c138b57)
![WhatsApp Image 2025-11-27 at 21 19 09_c72da73f](https://github.com/user-attachments/assets/18cb41f8-73a2-46b2-91ae-fc292b998a10)



## Procedure:
	Open MATLAB software
	Open a new script file.
	Type the program.
	Save and Execute the program.
	Click on the crossing point of the root locus to find the value of K and poles at the crossing point.
	From the value of K, analyse the stability.

## Program: 
num=[1] <br>
den=[1 15 50 0] <br>
sys=tf(num,den) <br>
rlocus(sys) <br>
[k poles]=rlocfind(sys) <br>

## Output:
<img width="1920" height="1080" alt="Screenshot 2025-11-16 222206" src="https://github.com/user-attachments/assets/33d0cc93-8595-4653-a4ee-d07a0457baa5" />



## Result:
Thus the root locus for the given transfer function was drawn and verified using MATLAB. The conditions for stability is 750
