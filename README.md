# mockup_dataset_flight
keep only mockup file


## prompt
mockup a 100000 row data set that use this "FlightID,FlightNumber,Date_Local,Departure_Local,Arrival_Local,Date_UTC,Departure_UTC,Arrival_UTC,Origin,Destination,Aircraft,ULD_Details,Total_ULDs,Status

1000,RG559,2025-01-18,7:30,15:15,2025-01-18,1:30,8:15,SIN,DXB,B737,AKE×17_P1P×12,29,Cancelled

1001,RG891,2025-06-16,8:15,11:15,2025-06-16,1:15,2:15,SYD,LAX,B787,RKN×9,9,Cancelled

1002,RG967,2025-06-06,9:45,14:45,2025-06-06,2:45,8:45,SIN,LHR,A380,AKE×12_RKN×3,15,Delayed

1003,RG611,2025-03-16,9:15,22:30,2025-03-16,1:15,15:30,HND,JFK,A350,PMC×1,1,Arrived

1004,RG569,2025-05-27,11:45,2:00,2025-05-27,5:45,20:00,CDG,LAX,A380,PMC×19_AMJ×3_P1P×5,27,Arrived" for a reference in condition below

1.random origin and destination

2.random aircraft type

3.in "ULD_Details" column must relate with aircraft type such as 'A380-800: Can load approximately 38 LD-3 (AKE) containers on the lower deck, or alternatively up to 13 standard wide pallets (PMC/PAJ) in place of containers. Sometimes, it's possible to do a combination of both, but not at the maximum for each.

B777-200: Up to 32 LD-3s or 10 pallets.

A350-900: Typical configurations are 36 LD-3s or up to 11 pallets.

A330-300: Around 32 LD-3s or 11 pallets.

B747-400: The main deck (for freighters) can take up to 30 pallets. The lower deck takes up to 32 LD-1 containers (similar to LD-3).

For other ULD types:

LD-6/LD-11: These fit most wide-bodies like A330, A340, A350, A380, 747, 767 (in smaller numbers), and 777.

LD-2: Mainly used on Boeing 767 models.

ULD Compatibility by Aircraft Type (abbreviated):

A380, A350, A340, A330, 747, 777, 787: Compatible with LD-3 (AKE), LD-6 (ALF), LD-11 (AMF), LD-7 pallet (PMC/PAJ), and related container types.

B767: Uses LD-2 (DPE, DPN) and can take LD-3s with some space inefficiency'

4.period in 1 year.


generate in CSV file and I can download.
