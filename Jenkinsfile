import java.text.SimpleDateFormat;
import java.util.Date;
import java.lang.System
def a
pipeline{
    agent any
    stages{
        stage('a'){
            steps{
                script{
                   
                    a = "aaaaa"
                    
                }
            }
        }

        stage('b'){
            steps{
                script{
                    SimpleDateFormat sdf = new SimpleDateFormat("YYYYMMdHHmmss")
                    def date = new Date()
                    String str = sdf.format(date)
                    println(str)

                    println("a:"+a)
                }
            }
        }
    }
}
