import groovy.json.JsonSlurper;
import groovy.json.JsonSlurperClassic ;
import groovy.json.JsonOutput;

@NonCPS
def jsonParse(def json) {
    new groovy.json.JsonSlurperClassic().parseText(json)
}

def toJSON(def json) {
    new groovy.json.JsonOutput().toJson(json)
}

def toSTRINGTOJSON(def json) {
    new groovy.json.JsonOutput().toJson(json)
}

def toJSON2(def json) {
    JsonOutput.prettyPrint(JsonOutput.toJson(json))
}

def TRAGET_INSTANCE_ID=""

pipeline { 
    agent any 
    
        stages {
            stage('TEST WEB HOOK') { 
                steps { 
                    script{
                      echo "webhook initiated"
                    }
                }
        }     
    }
}
