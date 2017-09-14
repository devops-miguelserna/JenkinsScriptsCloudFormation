node {
	stage 'Checkout'
		git url: 'https://github.com/miguel8810/CloudFormationLab.git'
	
	
	stage 'Ejecutor'
		sh "chmod 777 ${WORKSPACE}/Build-Scripts/deploy.sh"
		sh "${WORKSPACE}/Build-Scripts/deploy.sh"

}