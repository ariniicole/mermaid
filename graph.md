```mermaid
flowchart LR
A([Current Stream of Events])--Ariana checks B2g now/staff update sheets-->B([Form is Submitted])
B--PDF'S are received-->C[data enters Microsoft Form Excel Sheet]
B--A.S. manually fills-->D[A.S. ACCESS FOLDER]
D-->E[Suchetha Folder]
D===F[Ariana gets Form Info]
C===F
F-->G([File Updates])
G--Tax ID, System #, Cert #, firm email, cert/app type-->H[Ariana Fills Masterfile]
G--update masterfile-->I[Updates Pending Decision]
G-->J[makes corresponding graphs]
A==Ariana attends PANJNY Meeting===K[Email Process]
K--track ststaus of signed cover report-->L[Email Signed Cover Reports]
K-->M[Email Q&A Regarding Status]
L-->N[update pending decision]
M-->N
N===I
N-->O([update master file])
J-->O
I--Emails Armand-->P[updates pending decision google sheet]
P-->Q[Update unmotivated firms list]
P-->R[updates denial/withdrawal list]
