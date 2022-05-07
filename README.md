# Excel-Dispatch-System
This is automated dispatch system for a supervisor for parcel dilivery with up to 25 riders each having upto 100 parcels.
Each parcel with a unique tracking ID. As a result it displays a weekly or daily view of details like delivered, returned and cash etc. by just scannng the parcels.
Every Rider have to scan the parcel befor departure and after delvering them, scan again returned parcels with some reasons. that can be edited.
# How to Use
## Departure
Before scanning the delivery parcels you must have data of parcels to put in files with days names. like tn# tracking numbers in column a, names contact and address details cod amount of each parcel against trackings. do not disturb the formula in column f and g. and even donot shift these f, g columns, otherwise system will not work. but you may insert any data after these two columns. 
every day you will get data and put it in these files only once. this whole is for use of one week only. for next week use another folder of files including the dispatcher. 
to update all of the data properly open all weekly files. all value error should be removed.
open the dispathcer 1.62 named excel file and mark attandence in row 5 also in weekly report in column a, those could be irregular. and of your choice.
of the sheet named with day, like scan monday, mean its monday and you are scanning the parcels for cell b5, in column b, below cell b5. in cell b4 counter will start counting parcels that are availabe in friday file. if there is no data abailable in file then counter will not count it means the you must have scanned wrong barcode. for other rider write name or code in cell c5 and start scanning below it (cell c5) and so on.
open weekly report sheet to view what data you have scanned correctly, after making sure all is good and no unassigned tracking is left, you may insert a pending column to insert pending ones. now riders are good to go and deliver them on route.
## Debrif
after delivering and returning back to office, riders can scan there parcel in same excel sheet at column y and z, you may edit "efused"and "edispatched" your will.these are only tyes of reasons why parcels were returned. no third reason can be added.
after scanning in debriefing, view the results in weekly report sheet. you will get details of delivered, total returned , and cash amount to be collected from rider in each day.
