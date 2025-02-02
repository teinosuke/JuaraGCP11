### Jalankan perintah berikut di CloudShell

```
gcloud services enable documentai.googleapis.com
export ZONE=$(gcloud compute instances list document-ai-dev --format 'csv[no-heading](zone)')
gcloud compute ssh document-ai-dev --project=$DEVSHELL_PROJECT_ID --zone=$ZONE --quiet
```

* Pergi ke `Document AI` dari [sini](https://console.cloud.google.com/ai/document-ai?)

* Klik `Explore Processor`
* Pastikan nama processornya adalah `form-parser`

* Download file [form.pdf](https://storage.googleapis.com/cloud-training/document-ai/generic/form.pdf) ke komputer kita.

### Jalankan perintah berikut di CloudShell
* Copy paste ID Processor dari Form Parser sebelumnya
  
```
export PROCESSOR_ID=
```

### Jalankan perintah berikut di CloudShell
```
curl -LO raw.githubusercontent.com/QUICK-GCP-LAB/2-Minutes-Labs-Solutions/main/Create%20and%20Test%20a%20Document%20AI%20Processor/gsp924.sh

sudo chmod +x gsp924.sh

./gsp924.sh
```

### Selamat 🎉 Anda menyelesaikan Lab !
