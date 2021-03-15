# lista-1-para-p1
int main() {
	
  int a, b, c;
	
  printf("Digite 3 numeros:\n");
	scanf("%d %d %d", &a, &b, &c);
	
  if (a < c) {
		int tmp = c;
		c = a;
		a = tmp;
	}
	
  if (a < b) {
		int tmp = b;
		b = a;
		a = tmp;
	}
	
  if (b < c) {
		int tmp = c;
		c = b;
		b = tmp;
	}
   
    printf("%d %d %d", a, b, c);
}
