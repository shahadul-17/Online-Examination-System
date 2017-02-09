# Online-Examination-System
A simple Online Examination System written in Java (socket programming).

# Requirements
1) Java SE Runtime Environment (JRE) 6 or newer.

# Features
1) Server can handle multiple clients simultaneously.  
2) Server arranges different sequence of questions for different clients.  
3) If a question is not answered in a minute, that question will be answered automatically with a default answer (a).  
4) Next question will be sent by the server if the previous question is answered or timed out.  
5) Server sends the score along with the correct answers to the client after the examination is over.