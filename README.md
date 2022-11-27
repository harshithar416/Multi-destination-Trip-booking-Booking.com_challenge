# Multi-destination-Trip-booking-Booking.com_challenge

Dataset
The training dataset consists of over a million of anonymized hotel reservations, based on real data, with the following features: user_id - User ID

check-in - Reservation check-in date
checkout - Reservation check-out date
affiliate_id - An anonymized ID of affiliate channels where the booker came from (e.g. direct, some third party referrals, paid search engine, etc.)
device_class - desktop/mobile
booker_country - Country from which the reservation was made (anonymized)
hotel_country - Country of the hotel (anonymized)
city_id - city_id of the hotel’s city (anonymized)
utrip_id - Unique identification of user’s trip (a group of multi-destinations bookings within the same trip)

Evaluation criteria
The goal of the challenge is to predict (and recommend) the final city (city_id) of each trip (utrip_id). We will evaluate the quality of the predictions based on the top four recommended cities for each trip by using Precision@4 metric (4 representing the four suggestion slots at Booking.com website). When the true city is one of the top 4 suggestions (regardless of the order), it is considered correct.
