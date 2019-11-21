# Viðauki
## Dagbækur
https://github.com/AtliOskarsson/rob2b3u/wiki/Dagb%C3%B3k
## Kóði
```
#include "vex.h"

using namespace vex;    

int main() {
  // Initializing Robot Configuration. DO NOT REMOVE!
  vexcodeInit();
  LeftArm.spin(forward);
  RightArm.spin(forward);
  LeftMid.spin(forward);
  RightMid.spin(forward);
  RightBack.spin(reverse);
  LeftBack.spin(reverse);
  vex::task::sleep(1500);
  LeftArm.stop();
  RightArm.stop();
  LeftMid.stop();
  RightMid.stop();
}
```
