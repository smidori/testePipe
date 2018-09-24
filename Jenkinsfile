properties([
  parameters([
    string(name: 'DEPLOY_ENV', defaultValue: 'TESTING', description: 'The target environment', )
   ])
])


stage 'Checkout'
 node {
  deleteDir()
  checkout scm
  //sh 'diretorio=$(pwd)'
  sh 'export diretorio=$(pwd)'
  sh 'ls -la'
  echo '=========> ${JIRAKEY}'


print "Will deploy to ${DEPLOY_ENV}"
print "Will deploy to ${params.DEPLOY_ENV}"

test("qwqwqwqwqwqwq")

/*
stage('Deploy'){

         echo 'Push to Repo'
         sh './dockerPushToRepo.sh'

       }
*/

 }

 def test(def valor){
     print '-=-=-=--=> ' valor
       writeFile file: "setup2.properties", text: "a=b\nc=d\ne="
 }
