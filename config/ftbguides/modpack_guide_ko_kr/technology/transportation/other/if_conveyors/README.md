# 컨베이어 벨트

컨베이어 벨트(Conveyor Belt)는 아이템, 엔티티(몬스터 등), 심지어는 액체도 바라보는 방향으로 옮깁니다.
![흰색 컨베이어 벨트](item:industrialforegoing:conveyor)

![추출 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade)
![삽입 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade 1 1)
기본적으로 컨베이어 벨트는 엔티티만을 옮길 수 있습니다. 블록에서 아이템을 꺼내거나 집어넣을 수는 없습니다. 이런 기능을 위해서는 각각의 컨베이어 벨트에 추출/삽입 컨베이어 업그레이드를 적용해야 합니다.
![](conveyors.png)

기본적으로 컨베이어 벨트 위의 아이템은 가까이 접근한 플레이어가 주울 수 있습니다. 플라스틱을 컨베이어 벨트에 이동되고 있는 아이템을 주울 수 없도록 업그레이드할 수 있습니다.
발광석을 사용해 컨베이어 벨트의 속도를 올릴 수도 있습니다!

작동 방식을 변경하는 다른 여러 업그레이드들도 있습니다.

![](splitting.png)
![분할 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade 1 6)
분할 컨베이어 업그레이드(Splitting Conveyor Upgrade)를 적용한 컨베이어 벨트는 이동된 아이템 일부를 다른 컨베이어 벨트로 보낼 수 있습니다. 분할하고싶은 벨트의 원하는 방향에 업그레이드 아이템을 적용하세요. 빈손으로 우클릭해 설정 창을 열면 해당 방향의 가중치를 설정할 수 있습니다. 예시로, 두 방향으로 나눠진 컨베이어 벨트의 각각의 가중치가 둘다 1이라면 50%의 확률로 다른 방향으로 아이템이 이동합니다. 한쪽의 가중치가 2이고 다른 한쪽은 1이라면, 첫 번째 방향은 66%, 두 번째 방향은 33%의 확률로 아이템이 이동합니다.

![투하 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade 1 4)
투하 컨베이어 업그레이드(Dropping Conveyor Upgrade)는 컨베이어 벨트에서 아래방향에 있는 블록또는 바닥으로 아이템을 떨구도록 만듭니다. 우클릭해 화이트리스트/블랙리스트(허용/금지 항목)를 등록할 수 있습니다.

![감지 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade 1 2)
감지 컨베이어 업그레이드(Detection Conveyor Upgrade)는 컨베이어에 엔티티(몬스터나 아이템 등)가 지나갈 때 레드스톤 신호를 생성하도록 만듭니다. 우클릭해 GUI를 열 수 있고, 레드스톤 신호가 활성화될 아이템과 몬스터에 대한 화이트리스트/블랙리스트를 등록할 수 있습니다. 몬스터를 등록하기 위해서는 몹 구속 도구(Mob Imprisonment Tool)를 리스트에 넣으면 됩니다.

![이 순간 업그레이드는 3칸 위와 앞으로 움직이도록 설정되어 있습니다](blinking.png)
![순간 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade 1 5)
순간 컨베이어 업그레이드(Blinking Conveyor Upgrade)는 엔티티(몬스터와 플레이어를 포함한)를 설정된 거리만큼 위와 앞으로 순간이동시킵니다. 우클릭해 수직/수평 거리를 설정할 수 있고, 추가적으로 화이트리스트/블랙리스트도 설정할 수 있습니다. 액체를 텔레포트 시키지는 못합니다.

![점멸 컨베이어 업그레이드](item:industrialforegoing:conveyor_upgrade 1 3)
점멸 컨베이어 업그레이드(Bouncing Conveyor Upgrade)는 엔티티를 공중으로 날려보냅니다. 우클릭해 수직/수평 강도를 설정할 수 있고, 추가적으로 화이트리스트/블랙리스트도 설정할 수 있습니다.

이 업그레이드는 액체에도 적용됩니다!
![](lava.png)