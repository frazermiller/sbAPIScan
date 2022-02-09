# sbAPIScan
Google Safe Browsing (GSB) Bulk URL Scanning Tool

1. Open the scanning tool

![image](https://user-images.githubusercontent.com/99141651/153300189-1a77badb-bb20-4761-99cf-4279d8717b83.png)

2. Click "Choose File" and select your .txt file containing a list of URLs (one per line)

![image](https://user-images.githubusercontent.com/99141651/153300208-ac55e1be-dfd5-45e3-b68d-da155129e846.png)

3. Click "Scan" button for it to start scanning and output scan progress

![image](https://user-images.githubusercontent.com/99141651/153300224-a45250fe-8f69-4fa6-9d28-66c137ca6aea.png)

4. Once it has completed, you will be prompted that it has finished, click OK

![image](https://user-images.githubusercontent.com/99141651/153300248-05a3b9d5-c9ec-49dd-a649-3b16c457ef26.png)

5. Click the "Export" button and choose a filename. The file will export to <filename>.xlsx

![image](https://user-images.githubusercontent.com/99141651/153300277-17cd9c89-decd-49d9-b28c-f3a2bae2ed8d.png)

6. Open the Excel Sheet, where you can filter on "Detected" or "Clean"


Things to take note of:

- Usage is dependent on memory; stick to 1,000 lines per .txt file for speed
- You need to use your own GSB API key which you can get from the google cloud console: https://console.cloud.google.com/apis/library/safebrowsing.googleapis.com
- Once you have an API key, enter into the field that says API KEY HERE (before scanning)
