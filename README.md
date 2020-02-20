rdiff signature google.jpg >> old.bin
rdiff signature google_new.jpg >> new.bin
rdiff delta old.bin google_new.jpg >> delta.bin
rdiff patch old.bin delta.bin new.jpg
cp old.bin old.jpg