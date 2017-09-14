node {
	stage 'Checkout'
		git url: 'https://github.com/miguel8810/CloudFormationLab.git'
	stage 'Ejecutor'
		sh "${pwd}/Build-Scripts/deploy.sh"

}