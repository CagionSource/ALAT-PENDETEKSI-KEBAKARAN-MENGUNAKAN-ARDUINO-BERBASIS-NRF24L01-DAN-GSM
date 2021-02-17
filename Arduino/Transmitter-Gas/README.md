Flowchart  Alat sensor gas transmitter

![3](https://user-images.githubusercontent.com/78655390/107148893-417b4b00-6988-11eb-9a3e-46d92d461275.png)

Sama dengan Flowchart Alat sensor api transmitter, Flowchart  Alat sensor gas MQ-6 transmitter ini juga saat menjalankan alatnya, alatnya akan mencoba mencari koneksi dari Receivernya.
Setelah itu alatnya aktif mendeteksi gas. Jika terdeteksi api Buzzer di dalam alatnya akan menyalah dan akan menggirimkan data ke receiver untuk menggirimkan SMS.

Pemasangan pin komponen ke arduino

1. nRF24L01 :

                Ground  | GND          VCC  | 3.3V

                CE      | D7           CSN  | D8
                
                SCK     | D13          MOSI | D11
                
                SIMO    | D12
                
2. Buzzer : 
    
                + | D6                - | GND
                
3. Sensor Mq :

                Ground  | GND          VCC  | 5V

                
                A0      | A0
                
