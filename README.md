# abisko_2023

Fjällräven Classic 2023

- [abisko\_2023](#abisko_2023)
  - [calendar](#calendar)
  - [day plan](#day-plan)
  - [actions](#actions)

## calendar

    August 2023
Su Mo Tu We Th Fr Sa
       1  2  3  4  5
 6  7  8  9 10 11 12
13 14 15 16 17 18 19
20 21 22 23 24 25 26
27 28 29 30 31

## day plan

    ```yaml
    day_plan:
        08-aug-2023:
            - do: 
              - check-in to Hilton (stk)
            - details:
                - check-in to Hilton (stk):
                    name: Hilton Stockholm Slussen
                    address: Guldgränd 8, Box 15270, Stockholm 10465 SE
                    phone: +46851735300
                    confirmation: 3341169991
                    check-in time: 15:00
        09-aug-2023: 
            - do:
              - stay at Hilton (stk)
        10-aug-2023:
            - do: 
              - checkout of Hilton
              - travel to STK Central Station
              - travel from STK to Kiruna via train
            - details:
              - hotel:
                - checkout time: 12:00
              - travel to STK Centralstation:
                    start: tbd
                    end: tbd
                    mode: tbd
              - travel from STK to Kiruna via train:
                    details:
                        departure station: STK Centralstation
                        arrival station: Kiruna Central Station
                        number: vy tag 94
                        departure: 15:45
                        arrival: 05:47
                        total: 15 Hrs
        11-aug-2023: 
            do: 
                - arrive at Kiruna Central Station
                - travel from Kiruna Central Station to Airbnb home
                - check-in to Airbnb home
                - check-in to Camp Ripan
            details:
                - arrive in Kiruna:
                    arrival: 05:47 Hrs
                - check-in to Airbnb home:
                    check-in time: 15:00 Hrs
                    check-out time: 11:00 Hrs
                    address: Fotvägen 2, Kiruna N, Norrbottens län 981 91, Sweden
                - check-in to Camp Ripan:
                    reservation_number: 418436
                    reserved_on: 10-July-2023 02:47 Hrs
                    room: Hotellstuga Kiruna
                    arrival: 11-Aug-2023
                    departure: 12-Aug-2023
                    package_product: ORD
        12-aug-2023:
            do:
                - leave Airbnb
                - check-in at Camp Ripan
            details:
                - check-in to Camp Ripan:
                    reservation_number: 409948
                    reserved_on: 18-Apr-2023 23:53:00 Hrs
                    room: Hotellstuga Kiruna
                    arrival: 12-Aug-2023
                    departure: 13-Aug-2023
                    package_product: ORD
        13-aug-2023: begin Hike
        18-aug-2023:
            do: 
                - end hike
                - check-in to abisko turistation (PLRD12)
            details:
                - check-in to abisko turistation:
                    confirmation: PLRD12
                    supplier book number: XG72PX
                    check-in time: 15:00
                    check-out time: 10:00
                    address: ABISKO TURISTSTATION 2, 981 07 Abisko, Sweden
        19-aug-2023: 
            do:
                - checkout of Abisko Turistation
                - bus from Abisto Turistation to Kiruna Busstation
                - travel from Kiruna Busstation to Kiruna Central Station
                - train from Kiruna Cental Station to stk CentralStation
            details:
                - checkout of abisko turistation:
                    confirmation: PLRD12
                    supplier book number: XG72PX
                    check-in time: 15:00
                    check-out time: 10:00
                    address: ABISKO TURISTSTATION 2, 981 07 Abisko, Sweden
                - bus from Abisto Turistation to Kiruna Busstation:
                    confirmation: PLZ2669P0001
                    departure time: 11:00
                    arrival time: 12:20
                - travel from Kiruna Busstation to Kiruna Central Station:
                    mode: taxi / public transport (tbd)
                - train from Kiruna Cental Station to stk CentralStation:
                  - train_01:
                        name: vy tag 95
                        confirmation: PLZ2668I0001
                        departure time: 14:06
                        arrival time: 17:40
                  - train_02:
                        name: vy tag 91
                        confirmation: PLZ2668I0001
                        departure time: 17:54
                        arrival time: 06:27
        20-aug-2023: 
            do:
                - arrive at STK CentralStation
                - travel from STK CentralStation to Arlanda Airport
                - board flight from Arlanda
            details:
                - arrive at STK CentralStation:
                  - train_02:
                        name: vy tag 91
                        confirmation: PLZ2668I0001
                        departure time: 17:54
                        arrival time: 06:27
                - travel from STK CentralStation to Arlanda Airport:
                    carrier: Arlanda Express
                    order_number: 1542816
                    ticket_number: 1154911
                    ticket: see pdf
                    notes: |
==> Arlanda Express stops at two stations at Stockholm Arlanda Airport.
cotd. Arlanda South (Terminal 2, 3 and 4) and Arlanda North (Terminal 5).
==> Go to Arlanda North.
                - board flight from Arlanda:
                  - booking details:
                    booking_reference: 3K687O
                  - leg_1:
                        flight_number: SK489
                        src: ARN
                        dest: OSL
                        departure_time: 12:20
                        arrival_time: 13:20
                        terminal: 5
                        operated_by: Scandinavian Airlines
                        plane: AIRBUS A320
                  - layover_1: 30 minutes  
                  - leg_2:
                        flight_number: FI319
                        src: OSL
                        dest: KEF
                        departure_time: 13:50
                        arrival_time: 14:45
                        terminal: tbd
                        operated_by: Icelandair
                        plane: BOEING 757-200
                  - layover_2: 2h5m
                  - leg_3:
                        flight_number: FI645
                        src: KEF
                        dest: IAD
                        departure_time: 16:50
                        arrival_time: 19:15
                        terminal: tbd
                        operated_by: Icelandair
                        plane: BOEING 737 MAX 9
    ```

## actions

1. Confirm Camp Ripan
2. Cancel Airbnb as it's more expensive than Camp Ripan
3. Call IcelandAir:
   1. 1-800-223-5500
   2. Monday–Sunday 7:00 AM–1:00 AM GMT (Greenwich Mean Time) / 3:00 AM–9:00 PM ET (Eastern Time)
   3. Concerned about the short period of `layover_1`
4. Confirm with Hilton
   1. Need a quiet cool room (hopefully with a view)
      1. Fan
      2. Small fridge
      3. Microwave
