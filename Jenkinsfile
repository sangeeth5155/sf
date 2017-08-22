import groovy.json.JsonSlurperClassic
node {
    def SFDC_USERNAME
	def DEBUG_ISU=env.SFDX_DEBUG
    def HUB_ORG=env.HUB_ORG_DHC
    def SFDC_HOST=env.SFDC_HOST_DH
    def JWT_KEY_CRED_ID=env.JWT_CRED_ID_DH
	def rmgsplit
	

    def CONNECTED_APP_CONSUMER_KEY=env.CONNECTED_APP_CONSUMER_KEY_DH
    def toolbelt = tool 'toolbelt'
            println SFDC_HOST
            println JWT_KEY_CRED_ID
            println CONNECTED_APP_CONSUMER_KEY
            println HUB_ORG
			println toolbelt


    stage('checkout source') {
        // when running in multi-branch job, one must issue this command
        checkout scm
    }
   
            stage('mail')
            {
              mail (to: 'sangeetharajan.g@mstsolutions.com',
         subject: "Job '${env.JOB_NAME}' (${env.BUILD_NUMBER}) is waiting for input",
         body: "Please go to ${env.BUILD_URL}.");
         }
         }
node {
    def SFDC_USERNAME
	def DEBUG_ISU=env.SFDX_DEBUG
    def HUB_ORG=env.HUB_ORG_DHC
    def SFDC_HOST=env.SFDC_HOST_DH
    def JWT_KEY_CRED_ID=env.JWT_CRED_ID_DH
	def rmgsplit
	

    def CONNECTED_APP_CONSUMER_KEY=env.CONNECTED_APP_CONSUMER_KEY_DH
    def toolbelt = tool 'toolbelt'
            println SFDC_HOST
            println JWT_KEY_CRED_ID
            println CONNECTED_APP_CONSUMER_KEY
            println HUB_ORG
			println toolbelt
    
            stage('mail')
            {
              mail (to: 'sangeetharajan.g@mstsolutions.com',
         subject: "Job '${env.JOB_NAME}' (${env.BUILD_NUMBER}) is waiting for input",
         body: "Please go to ${env.BUILD_URL}.");
         }
         }
