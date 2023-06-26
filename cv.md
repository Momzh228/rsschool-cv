## Egor Rogozhin

### Contacts
- Email: rogozhin.egorka@mail.ru

### Summary
Programming school 21

### Skills
C

### Code-samples
long double s21_sqrt(double x) {
long double res;
if (x < 0 || S21_NAN == x) {
res = S21_NAN;
} else if (x == S21_INF) {
res = S21_INF;
} else {
res = s21_pow(x, 0.5);
}
return res;
}
###