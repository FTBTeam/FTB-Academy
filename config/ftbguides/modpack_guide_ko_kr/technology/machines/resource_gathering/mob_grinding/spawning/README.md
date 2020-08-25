# 몬스터 생성

자동으로 몬스터를 사냥하려면, 당연히 자동으로 몬스터를 생성해야겠죠. 이러한 내용들이 귀찮다면 단순히 어두운 방을 만들 *수는* 있지만, 별로 효율적이지 못하죠. 아래 블록/아이템들은 몬스터 생성 자동화를 도와줄 것입니다.

![안정된 몹 스폰기](item:draconicevolution:draconic_spawner)
드라코닉 에볼루션(Draconic Evolution)에서 추가된 코어들을 몬스터 스포너에 사용하면 안정된 몹 스폰기(Stabilized Mob Spawner)로 변환되어 아이템화됩니다.
더 비싼 코어를 사용할수록 몬스터가 더 자주 생성되고 스폰기의 제약이 줄어드는 등 생성된 스폰기의 성능이 좋아집니다. 등급이 낮은 스폰기는 중립 몬스터를 생성하려면 주변이 잔디가 있어야하고, 적대적 몬스터를 생성하려면 주변이 어두워야되는 등의 제약이 있습니다. 또한 높은 등급의 스폰기는 플레이어가 주변이 없어도 작동합니다.
레드스톤 신호를 줘서 스폰기의 작동을 멈출 수 있습니다.

![몹 소울](item:draconicevolution:mob_soul 1 0 {EntityName:"[Random-Display]"})
몹 소울(Mob Soul)은 드라코닉 에볼루션 모드의 무기나 저승사자 인챈트가 부여된 무기로 몬스터를 잡으면 낮은 확률로 드롭됩니다.
안정된 몹 스폰기에 몹 소울을 우클릭하면 스폰기에서 해당 몬스터를 생성하게 됩니다.

![Mob Swab](item:mob\_grinding\_utils:mob\_swab)
Mob Swab을 들고 몬스터를 우클릭하면 해당 몬스터의 DNA를 채취할 수 있습니다. Fluid XP가 담긴 양동이와 씨앗을 DNA가 묻은 Mob Swab과 함께 조합해 GM Chicken Feed를 만들고 닭에게 먹이면, 닭이 터지며 해당 몬스터 스폰알이 만들어집니다. 그냥 바닥에 우클릭해 몬스터를 소환할 수도 있지만, 몬스터 스포너에 우클릭해 해당 몬스터를 소환하는 스포너로 바꿀수도 있습니다.
스포너를 안정화하기 전에 이 방법을 사용할 수도 있습니다. 하지만 이미 안정된 스포너의 소환되는 몬스터를 바꿀 수 없습니다.

![스포너 체인저](item:actuallyadditions:item\_spawner\_changer)
스포너 체인저(Spawner Changer)를 들고 몬스터를 우클릭하면 그 몬스터를 체인저에 등록하고 없애버립니다. 몬스터가 등록된 스포너 체인저를 몬스터 스포너에 우클릭하면 해당 몬스터를 소환하는 스포너로 바뀝니다. 이 과정에서 스포너 체인저는 부서집니다.
스포너를 안정화하기 전에 이 방법을 사용할 수도 있습니다. 하지만 이미 안정된 스포너의 소환되는 몬스터를 바꿀 수 없습니다.

![몹 구속 도구](item:industrialforegoing:mob\_imprisonment\_tool)
몹 구속 도구(Mob Imprisonment Tool)를 들고 몬스터를 우클릭해 구속 도구 내부에 가둘 수 있습니다. 아무데나 우클릭해 몬스터를 다시 풀어줄 수도 있습니다.
![몹 복제기](item:industrialforegoing:mob_duplicator)
몹 복제기(Mob Duplicator)는 몹 파쇄기(Mob Crusher)에서 얻을 수 있는 숨결(Essence)와 RF를 사용해 몹 구속 도구 내부의 몬스터를 복제합니다. 주변에 몬스터가 너무 많다면 자동으로 멈춥니다.