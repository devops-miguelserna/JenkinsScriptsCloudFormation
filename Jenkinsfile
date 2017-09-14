node {
	stage 'Checkout'
		git url: 'https://github.com/miguel8810/CloudFormationLab.git'
	
	
	stage 'Ejecutor'
		sh "${WORKSPACE}/Build-Scripts/deploy.sh"

}