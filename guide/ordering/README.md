# Как записаться к барберу

1. **Выберите барбера** в каталоге мастеров
2. **Выберите услугу** (стрижка, бритье и т.д.)
3. **Выберите удобное время**
4. **Подтвердите запись**

> **Важно:** Отмена записи возможна за 2 часа до визита.

## Пример кода для записи

```java
public class BookingService {
    public Appointment createAppointment(String barberId, 
                                         String service, 
                                         LocalDateTime time) {
        Appointment appointment = new Appointment();
        appointment.setBarberId(barberId);
        appointment.setService(service);
        appointment.setTime(time);
        return appointment;
    }
}
```

## Ссылка

Узнайте больше о наших услугах на [официальном сайте](https://example.com).

<u>Подписка на регулярные визиты временно недоступна</u>

### Стоимость услуг

| Услуга | Стоимость |
|--------|-----------|
| Стрижка | 1500 ₽ |
| Бритье | 800 ₽ |
| Стрижка + Бритье | 2000 ₽ |
| Укладка | 500 ₽ |

