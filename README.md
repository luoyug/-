#include <stdio.h>

int main() {
    int BJT;
    int UTC;
    scanf("%d",&BJT);
    UTC=BJT+800;
    if (UTC>2400){
    UTC=UTC-2400;
    };
    printf("%d",UTC);

    return 0;
}
