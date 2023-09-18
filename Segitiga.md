# Pseudocode Luas Segitiga #

Deklarasi float alas, tinggi, sisi, luas, keliling

print "alas"\
input nilai alas
print "tinggi"
input nilai tinggi

luas = 0.5 * alas * tinggi
keliling = 3 * sisi 

print "luas" dan "keliling"

# Flowchart Luas dan Keliling Segitiga #

```mermaid
flowchart TD;
    A([Mulai])-->B{{float alas, tinggi, sisi, luas, keliling}}
    B-->C[/alas, tinggi, sisi/]
    C-->D(luas = 0.5 * alas * tinggi dan keliling = 3 * sisi)
    D-->E[/luas, keliling/]
    E-->F([selesai])
```