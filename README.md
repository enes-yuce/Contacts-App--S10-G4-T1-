# Gün Projesi: Contacts App

Şirketteki bir uygulamada UX olarak 2 sorun bulundu.:
1. Şirket içinde kullanılan Fihrist uygulamasında yeni kişi eklenince soldaki sideBar'da eklenen kişi listelenmiyor.
2. Bir kişi silinince soldaki listeden çıkmıyor.

Bu problemi sana atadılar.
Sen de bu şekildeki server state yönetimi en iyi yapabileceğin `@tanstack/react-query` ile yapmaya karar verdin.

@tanstack/react-query'i import ettin bile. Şimdi yapacakların:

- [ ] QueryClientProviderı App.jsxe eklemek.
- [ ] SideBarda tüm contactları çekmek için queryi yazmak. (useEffect'i silmelisin)
- [ ] Contact componentinde pathden aldığın contactId için query yazmak.(useEffect'i silmelisin)
- [ ] Contact componentinde adamı silmek için mutation yazmak.

**Dikkat**

- Yeni kişi eklediğinde Home sayfasına yönlenmeli
- Bir kişi silindiğinde Home sayfasına yönlenmeli
- Kodlar `tanStack.js` dosyasına yazılmalı.


Çalışma dosyalarım: src/services/tanStack.js, 
                    src/components/SideBar.jsx, 
                    src/components/Form.jsx, 
                    src/components/Contact.jsx, 
                    src/App.jsx