//multi dimensional array
//ali=50,60,70
//ayşe=60,80,90
//veli=60,70,80
//her ögrencinin not ortalamasını hesaplayın

string[] ogrenciler={"ali","ayşe","veli"};
int[,] notlar= new int[3,3];

//ali
notlar[0,0]=50;
notlar[0,1]=60;
notlar[0,2]=70;
//ayşe
notlar[1,0]=60;
notlar[1,1]=80;
notlar[1,2]=90;
//veli
notlar[2,0]=60;
notlar[2,1]=70;
notlar[2,2]=80;
var ortalama_ali=(notlar[0,0]+notlar[0,1]+notlar[0,2])/3;
var ortalama_ayşe=(notlar[1,0]+notlar[1,1]+notlar[1,2])/3;
var ortalama_veli=(notlar[2,0]+notlar[2,1]+notlar[2,2])/3;


Console.WriteLine($"{ogrenciler[0]} isimli ögrencinin not ortalamasi: {ortalama_ali}" );
Console.WriteLine($"{ogrenciler[1]} isimli ögrencinin not ortalamasi: {ortalama_ayşe}" );
Console.WriteLine($"{ogrenciler[2]} isimli ögrencinin not ortalamasi: {ortalama_veli}" );

