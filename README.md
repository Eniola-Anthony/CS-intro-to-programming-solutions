# chapter-6-Question-6
introductory to programming C# Personal solution

            int n = 1;

            int k = 1;
            
            
            Console.WriteLine("Enter a value for the Fibonacci members:");
            int a  = int.Parse(Console.ReadLine());
            Console.WriteLine("Enter a value for the Fibonacci members:");
            int b = int.Parse(Console.ReadLine());
            for (int i = a, r = b; i > 0 && r > 0 ; i--, r--)
            {
                n = n * i;
                k = k * r;

                
            }

            int result;
            result = n / k;
            Console.WriteLine(result);
