# EKOLİDER Skills

İzmir Ekonomi Üniversitesi Liderlik ve Yönetişim Uygulama ve Araştırma Merkezi (EKOLİDER) tarafından geliştirilen, Türkiye bağlamına uyarlanmış açık **Agent Skills** koleksiyonu.

Her skill, bir yapay zekâ asistanına (Claude, Copilot, Cursor ve Agent Skills standardını destekleyen diğer platformlar) belirli bir liderlik ve yönetişim işini nasıl yapacağını öğreten bir klasördür. Bir `SKILL.md` dosyası ve gerekirse şablon ve referans dosyalarından oluşur.

## Neden?

Açık skill ekosistemindeki sivil toplum ve yönetişim skill'lerinin büyük kısmı ABD mevzuatı ve kurumlarına göre yazılmıştır. Bu repo, Türkiye'deki öğrenci toplulukları, STK'ler, yerel yönetimler ve üniversite birimleri için yerel mevzuatı, kurumları ve pratiği tanıyan skill'ler sunar. Her skill yayımlanmadan önce merkez tarafından içerik, veri güvenliği ve etik açısından incelenir.

## Skill'ler

| Skill | Durum | Kimin için |
|---|---|---|
| [`kulup-liderligi`](skills/kulup-liderligi) | v0.1 taslak | Öğrenci kulübü yönetim kurulları |
| [`stk-proje-dongusu`](skills/stk-proje-dongusu) | v0.1 taslak | Yerel STK'ler |
| `stk-yonetisim-kontrolu` | planlandı | Dernek ve vakıf yöneticileri |
| `kent-konseyi-katilim` | planlandı | Kent konseyleri, yurttaş grupları |
| `etik-ikilem-vakasi` | planlandı | Liderlik Okulu katılımcıları |
| `yonetisim-endeksi-kodlayici` | planlandı | Araştırmacılar |
| `politika-notu-tr` | planlandı | Araştırmacılar, karar alıcılar |
| `ska-etki-raporu` | planlandı | Üniversite birimleri |
| `kurumsal-yz-politikasi` | planlandı | Kurumlar |
| `skill-denetimi` | planlandı | Skill kullanan tüm kurumlar |

## Kurulum

**Claude.ai:** Skill klasörünü zip'leyip Ayarlar → Yetenekler (Skills) bölümünden yükleyin.

**Claude Code / diğer ajanlar:** Klasörü `~/.claude/skills/` (veya platformunuzun skill dizini) altına kopyalayın:

```bash
git clone https://github.com/ekolider/ekolider-skills.git
cp -r ekolider-skills/skills/kulup-liderligi ~/.claude/skills/
```

## Katkı

Katkı kuralları ve inceleme süreci için [CONTRIBUTING.md](CONTRIBUTING.md) dosyasına bakın.

## Lisans

İçerik [CC BY 4.0](LICENSE) lisansıyla paylaşılır. Kaynak gösterildiği sürece kullanılabilir ve uyarlanabilir.

---

## English

Open, Türkiye-specific **Agent Skills** for leadership and governance, maintained by EKOLİDER (Center for Leadership and Governance, İzmir University of Economics). Most governance and nonprofit skills in the open ecosystem assume US law and institutions; these skills encode Turkish legislation, institutions and practice. Every skill is reviewed by the center for content accuracy, data protection and ethics before release. Licensed under CC BY 4.0.
