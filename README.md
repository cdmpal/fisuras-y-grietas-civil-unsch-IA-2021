gcloud builds submit --tag gcr.io/grietas-y-fisuras-muros-unsch/grietas-y-fisuras-civil-unsch  --project=grietas-y-fisuras-muros-unsch
gcloud run deploy --image gcr.io/grietas-y-fisuras-muros-unsch/grietas-y-fisuras-civil-unsch --platform managed  --project=grietas-y-fisuras-muros-unsch --allow-unauthenticated
