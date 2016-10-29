##Open API for OF@KOREN Playground Users!

![](https://raw.githubusercontent.com/SmartX-Labs/KOREN-Playground/master/images/OpenAPI.png)

본 페이지에서는 OF@KOREN Playground 사용자들의 편의성을 위한 모니터링 지원 기능에 대한
Open API를 제공합니다.

사용자 여러분께서는 아래 제공되는 Open API를 활용해

OpenStack 기반의 OF@KOREN Playground 환경의 상태를 실시간으로 감시할 수 있습니다.

Open API들은 요청(Request)에 대한 응답으로 대부분 JSON 방식의 데이터를 응답(Response)합니다.




MongoDB Collection List Data [GET]: 103.22.221.55:8181/mongodb_collection_list

Multiview User List Data [GET]: 103.22.221.55:8181/configuration_multiview_users

Physical Box List Data [GET]: 103.22.221.55:8181/configuration_pbox_list

Virtual Switch List Data [GET]: 103.22.221.55:8181/configuration_vswitch_list

Virtual Box List Data [GET]: 103.22.221.55:8181/configuration_vbox_list

Service List Data [GET]: 103.22.221.55:8181/configuration_service_list

Physical Box Path Status Data [GET]: 103.22.221.55:8181/configuration_pbox_path_status

Virtual Switch Status Data [GET]: 103.22.221.55:8181/configuration_vswitch_status

Flow Configuration Data [GET]: 103.22.221.55:8181/flow_configuration_sdn_controller_rt

Flow Status Data [GET]: 103.22.221.55:8181/flow_stats_sdn_controller_rt



(Python 3.4 / Django Framework 1.8 / pymongo lib 3.3.1 / MongoDB 3.0.5)
