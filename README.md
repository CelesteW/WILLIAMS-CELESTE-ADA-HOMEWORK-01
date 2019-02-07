# Williams-Celeste-Homework-01
# Challenge 7.1
v <- "Four score and seven years ago our fathers brought forth on this continent, a new nation, conceived in Liberty, and dedicated to the proposition that all men are created equal."
str_split(v, boundary("word"), n=Inf, simplify=FALSE)
b<- matrix( data= a[[1]], nrow=5, ncol=6)
b[seq(from=1, to=30, by=3)]
# Challenge 7.2
m<- matrix(data=1:80, nrow=8, ncol=10, byrow=FALSE)
x1<- m[,c(2,3,6)]
x2<- m[6:8,]
x3<- m[2:6,2:9]
# Challenge 7.3
a<- array (data=400:1, dim= c(5,5,5,4))
a[1,1,1,2]
a[2,3,2,]
a[1:5,1:5,3,3]
# Challenge 7.4
H<- "Haplorhini"
A<- "Anthropoidea"
PL<- "Platyrrhini"
C<- "Cebidae"
AT<- "Atelidae"
PI<- "Pitheciidae"
CA<- "Catarrhini"
CE<- "Cercopithecidae"
HY<- "Hylobatidae"
HO<- "Hominidae"
T<- "Tarsioidea"
TA<-"Tarsiidae"
S<- "Strepsirhini"
L<-"Lorisidea"
lo<- "Lorisidae"
G<-"Galagidae"
LE<- "Lemuroidea"
CH<- "Cheirogalaidae"
le<- "Lepilemuridae"
I<-"Indriidae"
lem<-"Lemuridae"
D<- "Daubentoniidae"
P<- "Primates"
p<- list(P, list(H, (list(A,list(PL,(list(C, AT, PI)),CA,(list(CE,HY,HO))),T,list(TA))),S,list(L,list(lo,G),LE,list(CH,le,I,lem,D))))
str(p)
# Challenge 7.5
a<- matrix(data= c(3,0,1,23,1,2,33,1,1,42,0,1,41,0,2), nrow=5, ncol=3, byrow=TRUE)
a
b<- data.frame(a)
b
b$X2= as.logical(b$X2)
b
b$X3<- factor(b$X3)
levels(b$X3)<- c("Female","Male")
b
str(b)