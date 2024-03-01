gcloud builds submit --tag gcr.io/dash-368722/portalichteste  --project=dash-368722


gcloud run deploy --image gcr.io/dash-368722/portalichteste --platform managed  --project=dash-368722 --allow-unauthenticated