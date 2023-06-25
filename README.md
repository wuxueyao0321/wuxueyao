# wuxueyao
wuxueyao
unsigned char RD(int i,int j){
float s=3./(j+99);
float y=(j+sin((i*i+_sq(j-700)*5)/100./DIM)*35)*s;
return (int((i+DIM)*s+y)%2+int((DIM*2-i)*s+y)%2)*127;
}
unsigned char GR(int i,int j){
float s=3./(j+99);
float y=(j+sin((i*i+_sq(j-700)*5)/100./DIM)*35)*s;
return (int(5*((i+DIM)*s+y))%2+int(5*((DIM*2-i)*s+y))%2)*127;
}
unsigned char BL(int i,int j){
float s=3./(j+99);
float y=(j+sin((i*i+_sq(j-700)*5)/100./DIM)*35)*s;
return (int(29*((i+DIM)*s+y))%2+int(29*((DIM*2-i)*s+y))%2)*127;
}
