Wesneday, January 22nd 2020

  this code consist to ask to the user the set of own email. below is the code:
  Given: first_name, last_name, year
  output: year.first_name.last_name@uwcisak.jp



```.c

int main(void) {
  char fname[20];
  char lname[20];
  int year;
  
  printf("Write your year, fname, lname\n");
  scanf("%i %s %s", &year, &fname, &lname);

  printf("%i.%s.%s@uwcisak.jp", year, fname, lname);
  
  
  return 0;
}
```
another example

```.c

int main(void) {
   char fname[20];
   char lname[20];
   int year;

  printf("Put down your fname\n");
  scanf("%s", &fname);
  printf("enter your last name\n");
  scanf("%s", &lname);
  printf("Write your year\n");
  scanf("%i", &year);

   printf("%i.%s.%s@uwcisak.jp", year, fname, lname);

 return 0;
 }

```
