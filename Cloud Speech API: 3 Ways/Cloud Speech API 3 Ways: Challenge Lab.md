### Jalankan perintah berikut di CloudShell

```
export ZONE=$(gcloud compute instances list lab-vm --format 'csv[no-heading](zone)')
gcloud compute ssh lab-vm --project=$DEVSHELL_PROJECT_ID --zone=$ZONE --quiet
```

* Pergi ke `Credentials` dari [sini](https://console.cloud.google.com/apis/credentials)
* Klik `Create Credential`

* Copy paste `API_KEY` dari `Credential`, dan nama file dari halaman course.

### Jalankan perintah berikut di CloudShell
```
export API_KEY=
export task_2_file_name=""
export task_3_request_file=""
export task_3_response_file=""
export task_4_sentence=""
export task_4_file=""
export task_5_sentence=""
export task_5_file=""
```
### Jalankan perintah berikut di CloudShell
```
curl -LO raw.githubusercontent.com/QUICK-GCP-LAB/2-Minutes-Labs-Solutions/main/Cloud%20Speech%20API%203%20Ways%20Challenge%20Lab/arc132.sh

sudo chmod +x arc132.sh

./arc132.sh
```

### Selamat 🎉 anda menyelesaikan Lab !

