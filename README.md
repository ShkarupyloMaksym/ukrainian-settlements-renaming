# Історичні перейменування українських населених пунктів / Historical Renamings of Ukrainian Settlements

## 🇺🇦 Українською

### Опис
Цей датасет містить історію перейменувань українських міст, сіл та селищ. Включає понад 1000 записів про зміни назв населених пунктів за різні історичні періоди.

### Структура даних
Файл `data/ukrainian_settlements_renaming.csv` містить наступні поля:

| Поле | Опис |
|------|------|
| `old_name` | Стара назва українською |
| `new_name` | Нова/поточна назва українською |
| `old_name_alt` | Альтернативні написання старої назви (польське, німецьке, ідиш, російське тощо), розділені крапкою з комою |
| `new_name_alt` | Альтернативні написання нової назви |
| `type` | Тип населеного пункту (місто, смт, село, селище) |
| `region` | Область |
| `district` | Район (якщо відомо) |
| `year_from` | Рік початку використання старої назви (якщо відомо) |
| `year_to` | Рік перейменування |
| `reason` | Причина перейменування (декомунізація, радянізація, українізація, десталінізація, імперське_перейменування) |
| `period` | Історичний період (козацька_доба, імперія_російська, імперія_австро-угорська, радянський, незалежність) |
| `source` | Джерело інформації |
| `latitude` | Широта (якщо відомо) |
| `longitude` | Довгота (якщо відомо) |
| `notes` | Додаткові примітки |

### Історичні періоди
- **Декомунізація 2015-2016**: Перейменування за Законом "Про засудження комуністичного та націонал-соціалістичного (нацистського) тоталітарних режимів в Україні"
- **Радянський період 1920-1991**: Перейменування на честь радянських діячів та символів
- **Російська імперія**: Русифікація козацьких та українських назв
- **Австро-Угорська імперія**: Історичні назви Галичини, Буковини та Закарпаття
- **Козацька доба**: Давні українські назви

### Джерела
- Постанови Верховної Ради України про декомунізацію
- Український інститут національної пам'яті (uinp.gov.ua)
- Енциклопедія історії України
- Вікіпедія

---

## 🇬🇧 English

### Description
This dataset contains the history of renamings of Ukrainian cities, towns, and villages. It includes over 1000 records of settlement name changes across different historical periods.

### Data Structure
The file `data/ukrainian_settlements_renaming.csv` contains the following fields:

| Field | Description |
|-------|-------------|
| `old_name` | Old name in Ukrainian |
| `new_name` | New/current name in Ukrainian |
| `old_name_alt` | Alternative spellings of old name (Polish, German, Yiddish, Russian, etc.), separated by semicolon |
| `new_name_alt` | Alternative spellings of new name |
| `type` | Settlement type (місто=city, смт=urban-type settlement, село=village, селище=settlement) |
| `region` | Oblast (region) |
| `district` | Raion (district), if known |
| `year_from` | Year when old name started being used, if known |
| `year_to` | Year of renaming |
| `reason` | Reason for renaming (декомунізація=decommunization, радянізація=sovietization, українізація=ukrainization, десталінізація=de-Stalinization, імперське_перейменування=imperial renaming) |
| `period` | Historical period (козацька_доба=Cossack era, імперія_російська=Russian Empire, імперія_австро-угорська=Austro-Hungarian Empire, радянський=Soviet, незалежність=independence) |
| `source` | Information source |
| `latitude` | Latitude, if known |
| `longitude` | Longitude, if known |
| `notes` | Additional notes |

### Historical Periods
- **Decommunization 2015-2016**: Renamings under the Law "On Condemnation of Communist and National Socialist (Nazi) Totalitarian Regimes in Ukraine"
- **Soviet Period 1920-1991**: Renamings in honor of Soviet figures and symbols
- **Russian Empire**: Russification of Cossack and Ukrainian names
- **Austro-Hungarian Empire**: Historical names of Galicia, Bukovina, and Transcarpathia
- **Cossack Era**: Ancient Ukrainian names

### Sources
- Resolutions of the Verkhovna Rada of Ukraine on decommunization
- Ukrainian Institute of National Remembrance (uinp.gov.ua)
- Encyclopedia of the History of Ukraine
- Wikipedia

---

## Ліцензія / License
CC0 1.0 Universal - See [LICENSE](LICENSE)
