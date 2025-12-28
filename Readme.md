    using System;

    class Task2
    {
    static void Main()
    {
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 },
            new int[] { 1, 3, 5, 7, 9 }
        };

        int digit1 = numberMatrix[1][3];
        int digit2 = numberMatrix[0][0];
        int digit3 = numberMatrix[1][4];

        string finalKey = $"{digit1}{digit2}{digit3}";

        Console.WriteLine(finalKey);
    }
    }
