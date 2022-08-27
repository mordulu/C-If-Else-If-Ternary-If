[Patika.dev](https://github.com/mordulu)


Dosyalarımın içinde yer alan program.cs'ye girilme zahmeti olmaması adına aşağıya çalışmamı önizleme olarak ekliyorum(süslü parantezler önizlemede hata verdiğinden konumlandırmalarına dikkat etmeyiniz)


# C-101-C 101 > C If Else If Ternary If

        internal class Program
        {
        private static void Main(string[] args)
        {
        {
            int time = DateTime.Now.Hour;

            if (time >= 6 && time < 11)
                Console.WriteLine("Günaydın");
            else if (time <= 18)
                Console.WriteLine("İyi Günler");
            else
                Console.WriteLine("İyi Geceler");

            string sonuc = time <= 18 ? "İyi Günler" : "İyi Geceler";

            sonuc = time >= 6 && time < 11 ? "Günaydın!" : "İyi Geceler!";

            Console.WriteLine(sonuc);

        }
        }
        }
