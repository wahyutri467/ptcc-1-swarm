# Docker Swarm

![Docker Swarm](pictures/swarm-big.jpg)


**Swarm** adalah sekelompok mesin yang menjalankan Docker dan menggabungkannya jadi satu _cluster_ atau akan disebut **nodes**. Setiap docker command nantinya akan dijalankan di atas cluster oleh **swarm manager**.


## Memahami Swarm Cluster
Swarm managers bisa menggunakan beberapa strategi dalam menjalankan container, Bisa `Emptiest Node` yang mengisi mesin yang paling kosong, atau `Global` yang memastikan setiap mesin mendapatkan _instance_ yang sama.

Swarm managers akan menjadi satu - satunya mesin di swarm yang bisa meng-eksekusi docker command, atau mengijinkan mesin yang lain untuk join swarm sebagai **worker**. Worker nantinya hanya akan ada untuk menambah kapasitas dan tidak punya otoritas yang lain.



