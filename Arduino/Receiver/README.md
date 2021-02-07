Flowchart Alat sensor api receiver



Alat sensor api receiver ini bisa berdiri sendiri tanpa adanya transmitter. 
Saat alatnya di aktifkan sensor nya langsung bisa bekerja mendeteksi api, jika sensor pada alat ini tidak mendeteksi adanya api maka alatnya akan  mengecek apakah ada kiriman data dari transmitter atau tidak. 
Kalau ada alat inikan mengaktifkan Buzzer dan menggirimkan SMS, kalau tidak ada data yang dikirimkan transmitter, maka alatnya akan loop dari pembacaan sensor api
