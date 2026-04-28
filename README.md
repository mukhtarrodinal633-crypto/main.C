# PROGDAS-TP-GIT

Jadi Program ini akan menjalankan sebuah program C sederhana yang fungsinya untuk memasukkan username dan pasword untuk login menggunakan program C

## Templat Program C

#include <stdio.h>
#include <string.h>

int main() {
    char username[50];
    char password[50];
    char correctUser[] = "admin";
    char correctPass[] = "AdminKikir";

    printf("=== LOGIN SEDERHANA ===\n");
    printf("Masukkan Username: ");
    scanf("%s", username);

    printf("Masukkan Password: ");
    scanf("%s", password);

    if (strcmp(username, correctUser) == 0 && strcmp(password, correctPass) == 0) {
        printf("Login berhasil!\n");
    } else {
        printf("Username atau Password salah!\n");
    }
    return 0;
}
