#과제 (4) 과제#03에서 반지름을 입력받아서, 원의 둘레와 원의 면적을 출력하는 프로그램을 작성하시오. 
#단 둘레는 소수점 1자리까지, 원의 면적은 소수점 2번째 자리까지 표시하시오. round 함수를 쓸 수 있겠으나, 출력시 포맷 기능을 활용하는 것을 권장함.

radius = input('원의 반지름을 입력하세요.')
R = math.pi * float(radius) * 2
area = math.pi * float(radius) ** 2

print(f"반지름 {radius}의 원 둘레: {R:.1f}")
print(f"반지름 {radius}의 원 면적: {area:.2f}")
