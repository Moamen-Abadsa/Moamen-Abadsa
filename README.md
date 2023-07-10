Hi there 👋 i'm Moamen El-Abadsa
I am a flutter developer with expertise in various languages and tools such Android , Java , kotlin , php , laravel , Dart , C# , Unity , swift , IOS , SQL


    class Moamen extends Developer
    {
        public String $name = "Moamen El-Abadsa";
        public String $position = "Flutter Developer";
    
        public function knowledge()
        {
            return collect([
                "Android",
                "Laravel",
                "Flutter",
                "Dart",
                "PHP",
                "Java",
                "Kotlin",
                "Unity",
                "Swift",
            ]);
        }

        public function contacts()
        {
            return collect([
                "LinkedIn" => "https://www.linkedin.com/in/moamen-s-el-abadsa-095025254/",
                "github" => "https://github.com/Muhanned-Anwar",
                "phone" => 0598624222,
            ]);
        }
    }
