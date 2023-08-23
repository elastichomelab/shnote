# DB 용어
# 도메인 
데이터베이스 내에서 특정 데이터 형식을 정의하고, 그 형식을 사용하여 컬럼의 데이터 타입을 설정할 수 있습니다. 도메인은 재사용성이 높아서 여러 테이블에서 같은 형식의 컬럼을 사용할 때 유용합니다.

# 스키마
데이터베이스 내에서 특정 사용자가 소유하는 개체들의 집합입니다. 스키마는 테이블, 뷰, 함수, 프로시저 등과 같은 데이터베이스 객체들을 포함합니다.

# 테이블
데이터를 저장하는 가장 기본적인 단위입니다. 테이블은 여러 개의 컬럼으로 구성되어 있으며, 각 컬럼은 데이터 타입을 가지고 있습니다. 데이터베이스 내에서 가장 많이 사용되는 객체 중 하나입니다.

# 뷰 
하나 이상의 테이블로부터 생성된 가상의 테이블입니다. 뷰는 테이블과 동일하게 쿼리를 통해 데이터를 조회할 수 있으나, 뷰를 조회하면 실제 데이터를 가지고 있는 테이블이 아니라 뷰를 생성할 때 지정한 조건에 따라 필요한 데이터만 가상으로 추출해내어 보여줍니다.

# 인덱스
데이터베이스에서 테이블에 대한 검색 성능을 높이기 위한 객체입니다. 인덱스는 테이블의 컬럼값을 기반으로 정렬된 데이터 구조를 갖추고 있으며, 특정 컬럼값으로 검색을 수행할 때 빠른 검색 속도를 제공합니다. 인덱스를 사용하면 데이터베이스에서 검색하는 시간을 줄일 수 있습니다.