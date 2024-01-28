1. Buat environment pake command `python3 -m venv .venv`
2. Masuk ke environment pakai command `. .venv/bin/activate`
![Activate Environment](Health-Insurance-Prediction/pics-of-docs/activate_env.png)

3. Buat file requirements.txt dan install menggunakan command `pip3 install -r requirements.txt` (apabila tidak bisa, lakukan instal secara satu per satu)
4. Buat app.py
![App.py](Health-Insurance-Prediction/pics-of-docs/app.png)

5. Buat model (file .pkl) ML dengan melakukan run pada modellingInsurance.ipynb
6. Setelah mendapatkan modelnya, pindahkan letak folder ‘packages’ ke dalam folder ‘modules’
7. Run app.py menggunakan command `flask run -–port 8000`
![Port](Health-Insurance-Prediction/pics-of-docs/run-port.png)

8. Buka aplikasi postman, klik import lalu paste command curl
9. Klik send untuk mendapatkan hasil prediksi
![Prediciton in Postman](Health-Insurance-Prediction/pics-of-docs/prediction-in-postman.png)
