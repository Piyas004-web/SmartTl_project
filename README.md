# SmartTl_project  

// Define the pins for the LEDs
const int redLight = 8;
const int yellowLight = 7;
const int greenLight = 6;

void setup() {
  // Initialize the LED pins as outputs
  pinMode(redLight, OUTPUT);
  pinMode(yellowLight, OUTPUT);
  pinMode(greenLight, OUTPUT);
}

void loop() {
  // Turn on the green light for 7 seconds
  digitalWrite(greenLight, HIGH);
  delay(7000);
  digitalWrite(greenLight, LOW);

  // Turn on the yellow light for 6 seconds
  digitalWrite(yellowLight, HIGH);
  delay(6000);
  digitalWrite(yellowLight, LOW);

  // Turn on the red light for 5 seconds
  digitalWrite(redLight, HIGH);
  delay(5000);
  digitalWrite(redLight, LOW);
}
