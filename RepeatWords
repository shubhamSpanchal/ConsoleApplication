            string statement ="";

            statement = Console.ReadLine();
            var StatementValue = statement.Split(' ');
            Dictionary<string, int> RepeatedWordCount = new Dictionary<string, int>();

            for(int i = 0 ; i < StatementValue.Length; i++)
            {
                if(RepeatedWordCount.ContainsKey(StatementValue[i]))
                {
                    int value= RepeatedWordCount[StatementValue[i]];
                    RepeatedWordCount[StatementValue[i]] = value + 1;
                }
                else
                {
                    RepeatedWordCount.Add(StatementValue[i],1);
                }
            }
            Console.WriteLine();

            foreach(KeyValuePair<string,int> kvp in RepeatedWordCount)
            {
                Console.WriteLine(kvp.Key + " " + " Counts is " + " " + kvp.Value);
            }

            Console.ReadKey();
