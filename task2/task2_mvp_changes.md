# Task2: Delta-диаграмма (только изменения к As-Is)

Создана отдельная диаграмма с изменениями относительно `As-Is`:
- [c4_container_delta_for_MVP.xml]

В диаграмме отражены только новые/измененные элементы:
1. MVP-блоки: `Patient Portal`, `Scheduling Service`, `Reminder Service (D-1)`, `RBAC/ABAC Access Policy`.
2. Privacy by Design блоки: `Consent & Categories`, `Data Tagging`, `Audit Log`, `Pseudonymization`.
3. Privacy-аналитический слой: `Analytics Mart`, `MVP BI Dashboard`.
4. Новый блок `Data Domains + Access`:
- Домены: `Identity`, `Contact`, `Appointment`, `Notification`.
- Дополнительно (опционально для MVP): `Minimal Clinical` (специализация врача, кабинет).
- RBAC: `patient`, `reception`, `doctor`.
- ABAC: `patient_id`, `doctor_id`, `purpose`.

Старые элементы из `As-Is` не дублируются; они указаны только как контекстный reference-блок.
