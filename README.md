# cloud run sample go
hello world by go

## Setup
gcloud builds submit --tag gcr.io/PROJECT-ID/sample-go
gcloud run deploy --image gcr.io/PROJECT-ID/sample-go --platform managed

