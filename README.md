# TicketOffice

## PIP

``` pip install git+https://github.com/jwoglom/npyscreen.git```

## Запускать только в полноэкранном режиме терминала!

### Реализованные классы(без класса интерфейса)

- Route - класс пути(id - id пути, train - класс поезда, time - время)
- Train - класс поезда(carriages - список вагонов)
- Carriage - общий класс для всех вагонов(name - название вагона, price - цена билета, max_seats_quantity - максимальное
  количество билетов, seats - список билетов)
    - SeatCarriage - класс сидячего вагона
    - EconomCarriage - класс эконом вагона
    - CoupleCarriage - класс купе вагона
    - FirstClassCarriage - класс вагона 1 класса
- Seat - класс места(id - id места - от 1 до max_seats_quantity, is_busy - "флаг занятости")