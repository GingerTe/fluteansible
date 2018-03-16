node {
   stage ("Get Latest Code") {
      checkout scm
   }
   
   try {
     stage ("Molecule test") {
        ansiColor('xterm') {
           sh 'molecule test'
        }
     }
   } catch(all) {
      currentBuild.result = "FAILURE"
      throw err
   }
}