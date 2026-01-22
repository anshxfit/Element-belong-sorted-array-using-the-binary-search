# Element-belong-sorted-array-using-the-binary-search
#include<iostream.h>
#include<conio.h>
void main()
{
clrscr();
int arr[10]=(5,10,15,20,25,30,35,40,45,50);
int low=0,high=9,mid,num, found=0;
cout<<"enter number to search:":
cin>>num:
while(low<=high){
mid=(low high)/2;
if (arr[mid==num]r){
found=1:
break;
}else if (num<arr[mid]){
high=mid-1;
}else{
low-mid+1;
}
}
if (found==1){
cout<<"\n the number"<<num<<"is found in the array.";
}else{
cout<<"\n the number"<<num<<"is not found in the array.";
}
getch();
}
