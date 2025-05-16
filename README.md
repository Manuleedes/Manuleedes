- 👋 Hi, I’m Emmanuel Lidigu and a Software engineer using Spring Framework and Java language
- Am also a DevOps engineer with knowledge in Docker, Kubernetes, Jenkins and TeamCity, Ansible and NGNX
- 👀 I’m interested in improving my skills in computer programmming and Software development through continous transition
- 🌱 I’m currently learning Web and Android development and cloud infrastructure with AWS
- 💞️ I’m looking to collaborate on with senior software developer and share ideas in order to solve realworld tech problems
- 📫 How to reach me , email Manuleedes@gmail.com, phone: +254745858081
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

I have created various projects in different languages to improve my coding skills and make myself ready and available for any software career jobs around

val Manuleedes = human {
    about {
        name = "Emmanuel Lidigu"
        company = Qhala Limited
        role = Developer_Advocate
    }

    tech {
        day("Kotlin", "Spring Boot", "React")
        night(".*".toRegex())
    }

    links {
        twitter = "@lidigu"
        website = "leedes.io"
    }
}

 @OptIn(ExperimentalResourceApi::class)
   @Composable
   fun App() {
       MaterialTheme {
           var greetingText by remember { mutableStateOf("Emmanuel, The great") }
           var showImage by remember { mutableStateOf(false) }
           Column(Modifier.fillMaxWidth(), horizontalAlignment = Alignment.CenterHorizontally) {
               Button(onClick = {
                   greetingText = "Hello, ${getPlatformName()}"
                   showImage = !showImage
               }) {
                   Text(greetingText)
               }
   +           TextField(greetingText, onValueChange = { greetingText = it })
               AnimatedVisibility(showImage) {
                   Image(
                       painterResource("compose-multiplatform.xml"),
                       null
                   )
               }
           }
       }
   }






