 # Instagram Auto Comment Bot 

Απλό script σε Python που κάνει **login στο Instagram** και αφήνει **αυτόματα σχόλιο** σε συγκεκριμένη ανάρτηση μέσω της βιβλιοθήκης `instagrapi`.



##  Απαιτήσεις

* Python **3.9+** 
* Instagram account 
* `instagrapi`

Εγκατάσταση βιβλιοθήκης:

```bash
pip install instagrapi
```

---

##  Ρυθμίσεις

Στο αρχείο `main.py` (ή όπως το ονομάσεις):

```python
user_name = 'username'
password = '******'
```

##  URL Ανάρτησης

Βάλε το link της ανάρτησης εδώ:

```python
media_url = 'https://www.instagram.com/p/XXXXXXXX/'
```

Το script μετατρέπει αυτόματα το URL σε `media_id`.

---



##  Εκτέλεση

```bash
python main.py
```

Αν όλα πάνε καλά θα δεις:

* `success sign in`
* `success comment`

Αλλιώς… exception.

---

##  Σημαντικές Προειδοποιήσεις

*  **ΜΗΝ** το τρέχεις μαζικά (spam = ban)
*  **ΜΗΝ** κάνεις πολλά σχόλια σε μικρό χρόνο
*  **ΜΗΝ** το τρέχεις από περίεργα IP / VPN


---



##  TL;DR

 Login
 Παίρνει post
 Αφήνει σχόλιο
 Logout

