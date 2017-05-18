node {
   def index
   stage('Preparation') { // for display purposes
      // Get some code from a GitHub repository
      git 'https://github.com/jorcama/firstrepo'
   }
   stage('Read File') {
     echo 'echo any file name'
     
     index = readFile ('index.html')
     
     echo 'echo any file name' 
   }
   stage('Show File') {
     echo index
     
   }
}
