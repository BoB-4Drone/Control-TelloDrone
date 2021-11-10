# Control-TelloDrone

uint8_t header;
uint16_t size;
uint8_t CRC_8;  // header ~ size
uint8_t type;
uint16_t msg_id;  // command type
uint16_t seq_no;  // sequence
uint8_t payload;
uint16_t CRC_16;  // header ~ payload
