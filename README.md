
using System.Linq.Expressions;

namespace Recatngle
{
    internal class Rectangle
    {
        static void Main(string[] args)
        {
            double widthOfRectangle, lenghtOfRectangle, area;

            try
            {
                Console.WriteLine("Please enter a value for the witdth of rectangle");
                widthOfRectangle = double.Parse(Console.ReadLine());

                Console.WriteLine("Please enter a value for the lenght of rectangle");
                lenghtOfRectangle = double.Parse(Console.ReadLine());


                area = widthOfRectangle * lenghtOfRectangle;


                Console.WriteLine("Input -> width: " + widthOfRectangle);
                Console.WriteLine("Input -> lengt: " + lenghtOfRectangle);
                Console.WriteLine("-------------");
                Console.WriteLine(" Result is: ");
                Console.WriteLine("Area of rectangle: " + area);
            }
            catch (FormatException e )
            { 
                Console.WriteLine("please enter only positive number"); 

            }
            catch ( Exception b )
            {
                Concole.Write
            }
            


        }
    }
}
