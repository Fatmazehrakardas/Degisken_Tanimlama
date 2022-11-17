# Degisken_Tanimlama
Değişken ve Veri Tipleri 

using System;
namespace degisken
{
    class Program
    {
        public static void Main(string[] args)
        {
            Console.WriteLine("Hello World!");
            int deger=2;
            Console.WriteLine(deger);
            string degisken=null;
            string Degisken=null;
            string veri_türü=null;
            byte b=5;
            sbyte c=5; //1 byte

            short s=5;
            ushort us=5;// 2byte

            Int16 i16=2; // 2 byte
            int i=2;     // 4 byte
            Int32 i32=2; // 4 byte
            Int64 i64=2; // 8 byte

            uint uı=2; // 4 byte
            long l=4; // 8 byte
            ulong ul=2; // 8 byte

            //reel sayılar 
            float f=4;  // 4 byte 
            double d=3; // 8byte
            decimal de=6; //16 byte

            char ch='6';// 2 byte
            string lk="8"; // sınırsız

            bool be=false;

            DateTime dt= DateTime.Now;

            object o1="x";
            object o2='y';
            object o3=4;
            object o4=4.3;

            // string ifadeler
             string str=string.Empty;
             str= "zehra";
             string ad="zehra";
             string soyad= "kardaş";
             string tamad=ad+" "+soyad;

             // integer tanımlama
              int integer1=5;
              int integer2=3;
              int integer3= integer1*integer2;

              // boolean 
              bool bool1=19>6;

              //degisken donusumleri

              string str20="20";
              int int20=20;

              string yenideger= str20+ int20.ToString();
              Console.WriteLine(yenideger); // çıktısı 2020
              int yeni_deger=int20+Convert.ToInt32(str20);
              Console.WriteLine(yeni_deger);// çıktısı 40

              int int22= int20+int.Parse(str20);//cıktısı 40

              // date time
              string datetime= DateTime.Now.ToString("dd.MM.yyyy");
              Console.WriteLine(datetime);
              string datetime2= DateTime.Now.ToString("dd/MM/yyyy");
              Console.WriteLine(datetime2);

              //saat
              string hour= DateTime.Now.ToString("HH:mm");
              Console.WriteLine(hour);



        }
    }
}

[patika.dev](https://app.patika.dev/)
