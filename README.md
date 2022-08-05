- 👋 Hi, I’m @ASAIWEI
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
ASAIWEI/ASAIWEI is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include "acllib.h"
#include <stdio.h>

int Setup()
{
	initWindow("te", 30,30,255,255); 
	beginPaint();
	int i, j;
	for ( i=0; i<255; i++ ) {
		for ( j=0; j<255; j++ ) {
			putPixel(i,j,RGB(i,j+i,j));
		}
	}
	endPaint();
	return 0;
}
