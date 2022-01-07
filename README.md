gcloud builds submit --tag gcr.io/grietas-y-fisuras-muros-unsch/fisuras-y-grietas-civil-unsch-IA-2021  --project=grietas-y-fisuras-muros-unsch
gcloud run deploy --image gcr.io/grietas-y-fisuras-muros-unsch/fisuras-y-grietas-civil-unsch-IA-2021 --platform managed  --project=grietas-y-fisuras-muros-unsch --allow-unauthenticated
