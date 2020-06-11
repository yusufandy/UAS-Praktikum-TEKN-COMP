# Minggu 14 (Kubernetes for Beginners)

1. Menjalankan perintah ls.

    ![1](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/1.png)

2. Inisialisasi cluster.

    ![2](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/2.png)
    ```
    Terlihat bahwasanya cluster telah berhasil di inisialisasi.
    ```
3. Menjalankan perintah kubectl apply -n kube-system -f \
    "https://cloud.weave.works/k8s/net?k8s-version=$(kubectl version | base64 |tr -d '\n')".

    ![3](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/3.png)

4. Mengcloning repository dockercoins.

    ![4](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/4.png)

5. Berpindah ke direktori hasil repo yang telah berhasil di clone dan menjalankan perintah docker-compose up.

    ![5](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/5.png)

6. Menjalankan perintah kubectl get node.

    ![6](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/6.png)
    ```
    Terlihat bahwasanya terdapat 1 buah node yang siap digunakan.
    ```
7. Menjalankan perintah kubectl get nodes -o wide.

    ![7](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/7.png)
    ```
    Terlihat bahwasanya terdapat 1 buah node yang siap digunakan.
    ```
8. Menjalankan perintah kubectl get no -o yaml.

    ![8](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/8.png)
    ![9](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/9.png)
    ```
    Terlihat bahwasanya menampilkan informasi yang lebih detail.
    ```
9. Menjalankan perintah kubectl get nodes -o json |
      jq ".items[] | {name:.metadata.name} + .status.capacity".

    ![10](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/10.png)
    ![11](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/11.png)
    ```
    Terlihat bahwasanya menampilkan informasi node dengan format JSON.
    ```
10. Menjalankan perintah kubectl get services.
    ![12](https://github.com/yusufandy/UAS-Praktikum-TEKN-COMP/blob/master/12.png)
    ```
    Terlihat bahwasanya menampilkan service kubernetes yang sedang berjalan.
    ```

