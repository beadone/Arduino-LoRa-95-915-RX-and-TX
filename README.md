# LoRa_95_915_RX
arduino and hope rf95 radio simple receiver and acknowledge code.
It has been changed from code found on the interent to have

1. 915 mHz
2. Uses it's own simple interupt timer in the TX code because it seemed that the  (rf95.waitAvailableTimeout(5000)) was not working and hence the wait loop for the ack is different
3. The RX code sends back a packet with a count
