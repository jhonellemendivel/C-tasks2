    class Task2
    {
    static void Main(string[] args)
    {
        // Row 0: Even numbers
        // Row 1: Odd numbers
        int[][] numberMatrix = new int[][]
        {
            new int[] { 2, 4, 6, 8, 10 },
            new int[] { 1, 3, 5, 7, 9 }
        };

        Console.WriteLine("The number matrix has been initialized.");

        // Extract digits based on clues
        int digit1 = numberMatrix[1][3];
        int digit2 = numberMatrix[0][0];
        int digit3 = numberMatrix[1][4];

        // Combine into 3-digit key string
        string finalKey = $"{digit1}{digit2}{digit3}";

        // Display the result
        Console.WriteLine($"The password is: {finalKey}");
    }

