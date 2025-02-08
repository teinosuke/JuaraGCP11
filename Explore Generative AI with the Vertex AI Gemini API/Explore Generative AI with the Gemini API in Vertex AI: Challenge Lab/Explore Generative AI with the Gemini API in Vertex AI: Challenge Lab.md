# Explore Generative AI with the Gemini API in Vertex AI: Challenge Lab

## Step 1

* Buka `Cloud Shell`, dan jalankan perintah berikut
  ```bash
  pip3 install --upgrade --user google-cloud-aiplatform
  ```
* Jalankan lagi perintah berikut di `CloudShell`
  ``` bash
  PROJECT_ID="Filled in at lab startup."
  LOCATION="Filled in at lab startup."
  API_ENDPOINT=${LOCATION}-aiplatform.googleapis.com
  MODEL_ID="gemini-1.0-pro"
  ```
## Step 2

  Buka `Vertex AI > Workbench` di [sini](https://console.cloud.google.com/vertex-ai/workbench?project=qwiklabs-gcp-03-306580a57ab8)

## Step 3
* Klik pada `nama file` notebook
* Pada dialog `Select Kernel` pilih `Python 3`
* Upload file `*.ipynb` yang ada pada folder ini  
