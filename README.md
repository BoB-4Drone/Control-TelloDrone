# Control-TelloDrone

uint8_t header;
uint16_t size;
uint8_t CRC_8;  // header ~ size
uint8_t type;
uint8_t msg_id;
uint8_t msg_id1;
uint8_t seq_no;
uint8_t seq_no1;
uint8_t payload;
uint16_t CRC_16;  // header ~ payload
