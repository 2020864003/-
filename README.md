namespace Stack {
    public class App {
        public App () {
            Stack stack = new Stack (10);

            stack.Push (1);
            stack.Push (2);
            stack.Push (3);
            stack.Push (4);

            var data = stack.Pop ();
            System.Console.WriteLine (data);

        }
    }
}
