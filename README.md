# Codelabs link
https://codelabs.developers.google.com/codelabs/cloud-run-hello-python3?hl=en#3

# Flow
Python Code -> Cloud Build -> Container Image -> Artifact Registry -> Cloud Build -> Cloud Run

# Deploy the application to Cloud Run:
gcloud run deploy helloworld-python --source . --platform managed --region 'asia-southeast1' --allow-unauthenticated
  

