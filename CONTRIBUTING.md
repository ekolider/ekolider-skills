# Katkı Rehberi

## Yeni skill önermek
1. `skills/_sablon/` klasörünü kopyalayın ve skill adıyla yeniden adlandırın (küçük harf, Türkçe karakter yok, tire ile: `stk-yonetisim-kontrolu`).
2. `SKILL.md` dosyasını doldurun. Gövde 500 satırı geçmemeli; uzun içerik `references/` altına.
3. Pull request açın. Açıklamada skill'in kimin hangi işini çözdüğünü ve hangi mevzuata dayandığını belirtin.

## İnceleme ölçütleri (EKOLİDER denetimi)
Her PR birleştirilmeden önce şu açılardan incelenir:
- **Doğruluk:** Mevzuat atıfları güncel mi, kaynağı belirtilmiş mi? Emin olunmayan bilgi "doğrulayın" notuyla işaretlenmiş mi?
- **Veri güvenliği:** Skill, kullanıcıdan gereksiz kişisel veri istiyor mu? KVKK'ya aykırı bir işlem öneriyor mu?
- **Güvenlik:** Dış adrese veri gönderen, izinsiz komut çalıştıran veya talimat enjeksiyonuna açık bir bölüm var mı?
- **Etik:** Skill'in ürettiği çıktı, kapsayıcılık ve hesap verebilirlik ilkeleriyle uyumlu mu?
- **Sınır:** Skill, hukuki veya mali danışmanlık yerine geçtiğini ima ediyor mu?

## Sürümleme
Her skill'in başında `version` alanı tutulur. Mevzuat değişikliği gerektiren güncellemeler ara sürüm (0.2 → 0.3), yapısal değişiklikler ana sürüm artırır.
