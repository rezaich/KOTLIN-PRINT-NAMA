# KOTLIN-PRINT-NAMA
fun main() {      while (true) {         print("Mulai y/n : ")         val mulai= readLine()         if(mulai == "y"){             print("Name: ")             val name = readLine()             print("Age: ")             val age = readLine()             print("Job : ")             val job = readLine()              val templateBio = """     +==========================================+     | BIO DATA PROGRAMMER             +------------------------------------------+     | Nama lengkap  : $name     | Age           : $age     | Pekerjaan     : $job     +==========================================+     """              println(templateBio)         }         if (mulai == "n")             break     } }
