node {
	stage 'Checkout'
		git url: 'https://github.com/miguel8810/CloudFormationLab.git'
	
	def SCRIPTS_DIR="$( cd "$( dirname "${BASH_SOURCE[0]}" )" && pwd )"
	stage 'Ejecutor'
		sh "${pwd}/Build-Scripts/deploy.sh"

}