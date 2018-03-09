Session ID Unknown 이슈
ID : wogml9850_1509803501

2018/01/25

```
281	|	13:35:47:490 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
282	|	13:35:47:494 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
283	|	13:35:47:497 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
284	|	13:35:47:500 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
285	|	13:35:47:521 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
286	|	13:35:47:522 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
287	|	13:35:47:641 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
288	|	13:35:48:214 (UTC)	|	-[AppDelegate applicationWillResignActive:] line 2682 $ Function Called.
289	|	13:35:48:216 (UTC)	|	-[AppDelegate applicationWillResignActive:] line 2684 $ Before function proceed ViewControllers : (
290	|	13:35:48:873 (UTC)	|	-[AppDelegate applicationDidEnterBackground:] line 651 $ Function Called.
291	|	13:35:48:873 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
292	|	13:35:48:877 (UTC)	|	-[ChatViewController viewDidDisappear:] line 478 $ Function Called.
293	|	13:35:48:879 (UTC)	|	-[ChatViewController sendUpdateLastReadNoRequest] line 882 $ Function Called.
294	|	13:35:48:885 (UTC)	|	+[JSONController transToJson:] line 36 $ {
295	|	13:35:48:886 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
296	|	13:35:48:888 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateLastReadNo
297	|	13:35:49:558 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
298	|	13:36:51:890 (UTC)	|	Socket Error : ["Session ID unknown"] (null)
299	|	13:36:51:899 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
300	|	13:36:51:900 (UTC)	|	Socket Reconnect : ["Session ID unknown"] (null)
301	|	13:36:51:903 (UTC)	|	Socket ReconnectAttempt : [-1] (null)
302	|	13:36:51:906 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
303	|	13:36:51:915 (UTC)	|	Socket Error : ["Session ID unknown"] (null)
304	|	13:36:51:916 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
305	|	13:36:52:115 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
306	|	13:36:52:118 (UTC)	|	[Trost_iOS.SocketIOController sendEnterCounseling()]
307	|	13:36:52:121 (UTC)	|	-[ChatViewController showLoadingViewWithWarnStr:] line 4843 $ Function Called.
308	|	13:36:52:306 (UTC)	|	[Trost_iOS.SocketIOController loadMessage(msgArray:)]
309	|	13:36:52:315 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtTop(msgArray:)]
310	|	13:36:52:316 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtBetween(msgArray:)]
311	|	13:36:52:322 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
312	|	13:36:52:363 (UTC)	|	-[ChatViewController endRefreshController] line 5136 $ Function Called.
313	|	13:36:52:365 (UTC)	|	-[ChatViewController tViewScrollToBottomWithRow:] line 5142 $ Function Called.
314	|	13:36:52:641 (UTC)	|	-[ChatViewController stopLoadingIndicator] line 5130 $ Function Called.
315	|	13:36:52:653 (UTC)	|	Socket loadCounselingListOfClient (null)
316	|	13:36:52:656 (UTC)	|	-[MenuViewController recvCounselingListInfoForClientWithCounselingListInfo:] line 2064 $ Function Called.
317	|	13:36:52:666 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2074 $ Function Called.
318	|	13:36:52:667 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
319	|	13:36:52:687 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
320	|	13:36:52:691 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
321	|	13:36:52:694 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
322	|	13:36:52:698 (UTC)	|	-[AppDelegate removeIndicatorView] line 790 $ Function Called.
323	|	13:36:52:701 (UTC)	|	-[ClientCounselingViewController updateInfo:] line 507 $ Function Called.
324	|	13:36:52:707 (UTC)	|	-[MenuViewController badgeDrawer] line 1189 $ Function Called.
325	|	13:36:52:708 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
326	|	13:37:55:576 (UTC)	|	Socket Error : ["Session ID unknown"] (null)
327	|	13:37:55:578 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
328	|	13:37:55:611 (UTC)	|	Socket Reconnect : ["Session ID unknown"] (null)
329	|	13:37:55:615 (UTC)	|	Socket ReconnectAttempt : [-1] (null)
330	|	13:37:55:618 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
331	|	13:37:55:649 (UTC)	|	Socket Error : ["Session ID unknown"] (null)
332	|	13:37:55:650 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
333	|	13:37:55:836 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
334	|	13:37:55:837 (UTC)	|	[Trost_iOS.SocketIOController sendEnterCounseling()]
335	|	13:37:55:839 (UTC)	|	-[ChatViewController showLoadingViewWithWarnStr:] line 4843 $ Function Called.
336	|	13:39:25:011 (UTC)	|	[Trost_iOS.MyInfoView draw]
337	|	13:39:25:017 (UTC)	|	-[EmojiPlusView drawRect:] line 57 $ Function Called.
338	|	13:39:25:030 (UTC)	|	[Trost_iOS.MessageInputView draw]
339	|	13:39:25:656 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 583 $ Function Called.
340	|	13:39:25:656 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 584 $ Navigation ViewControllers at DidBecome start : (
341	|	13:39:25:661 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
342	|	13:39:25:672 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
343	|	13:39:25:673 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
344	|	13:39:25:683 (UTC)	|	-[AppDelegate sendTokenInfo] line 971 $ Function Called.
345	|	13:39:25:688 (UTC)	|	+[JSONController transToJson:] line 36 $ {
346	|	13:39:25:689 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
347	|	13:39:25:691 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateToken
348	|	13:39:25:696 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 645 $ Navigation ViewControllers at DidBecome end : (
349	|	13:39:25:718 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke line 2855 $ Error : Error Domain=NSURLErrorDomain Code=-1009 "인터넷 연결이 오프라인 상태입니다." UserInfo={NSUnderlyingError=0x15b0bfa70 {Error Domain=kCFErrorDomainCFNetwork Code=-1009 "(null)" UserInfo={_kCFStreamErrorCodeKey=50, _kCFStreamErrorDomainKey=1}}, NSErrorFailingURLStringKey=https://trost.co.kr:1242/updateToken, NSErrorFailingURLKey=https://trost.co.kr:1242/updateToken, _kCFStreamErrorDomainKey=1, _kCFStreamErrorCodeKey=50, NSLocalizedDescription=인터넷 연결이 오프라인 상태입니다.}
350	|	13:39:25:720 (UTC)	|	-[AppDelegate showAlert:] line 3028 $ Function Called.
```



ID : dmea615_1516847759

2018/01/25

```
133	|	04:19:39:578 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
134	|	04:19:39:579 (UTC)	|	-[ChatViewController recvMessageTypingScroll] line 5163 $ Function Called.
135	|	04:19:39:581 (UTC)	|	-[ChatViewController tViewScrollToBottomWithRow:] line 5142 $ Function Called.
136	|	04:19:47:415 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
137	|	04:19:47:415 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
138	|	04:19:47:416 (UTC)	|	-[ClientCounselingViewController refresh] line 395 $ Function Called.
139	|	04:19:47:418 (UTC)	|	-[MenuViewController badgeDrawer] line 1189 $ Function Called.
140	|	04:19:47:419 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
141	|	04:19:47:420 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
142	|	04:19:47:421 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
143	|	04:19:47:428 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
144	|	04:19:47:483 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
145	|	04:19:47:925 (UTC)	|	[Trost_iOS.SocketIOController recvMessageStopTyping()]
146	|	04:19:47:927 (UTC)	|	[Trost_iOS.SocketIOController removeTypingCell()]
147	|	04:19:47:928 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
148	|	04:19:48:323 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
149	|	04:19:48:324 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1520 $ Response :
150	|	04:21:09:661 (UTC)	|	Socket Error : ["Session ID unknown"] (null)
151	|	04:21:09:662 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
152	|	04:21:09:662 (UTC)	|	Socket Reconnect : ["Session ID unknown"] (null)
153	|	04:21:09:663 (UTC)	|	Socket ReconnectAttempt : [-1] (null)
154	|	04:21:09:663 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
155	|	04:21:09:737 (UTC)	|	Socket Error : ["Session ID unknown"] (null)
156	|	04:21:09:738 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
157	|	04:21:09:871 (UTC)	|	Socket StatusChange : [SocketIO.SocketIOClientStatus] (null)
158	|	04:21:09:873 (UTC)	|	[Trost_iOS.SocketIOController sendEnterCounseling()]
159	|	04:21:09:873 (UTC)	|	-[ChatViewController showLoadingViewWithWarnStr:] line 4843 $ Function Called.
160	|	04:21:29:805 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 583 $ Function Called.
161	|	04:21:29:805 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 584 $ Navigation ViewControllers at DidBecome start : (
162	|	04:21:29:807 (UTC)	|	-[AppDelegate sendTokenInfo] line 971 $ Function Called.
163	|	04:21:29:807 (UTC)	|	+[JSONController transToJson:] line 36 $ {
164	|	04:21:29:808 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
165	|	04:21:29:808 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateToken
166	|	04:21:29:808 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 645 $ Navigation ViewControllers at DidBecome end : (
167	|	04:21:30:188 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
168	|	04:21:30:189 (UTC)	|	-[AppDelegate recvTokenInfo:] line 1007 $ Function Called.
169	|	04:21:30:190 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
170	|	04:21:31:406 (UTC)	|	-[AppDelegate applicationWillResignActive:] line 2682 $ Function Called.
171	|	04:21:31:407 (UTC)	|	-[AppDelegate applicationWillResignActive:] line 2684 $ Before function proceed ViewControllers : (
172	|	04:21:31:473 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 583 $ Function Called.
173	|	04:21:31:473 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 584 $ Navigation ViewControllers at DidBecome start : (
174	|	04:21:31:475 (UTC)	|	-[AppDelegate sendTokenInfo] line 971 $ Function Called.
175	|	04:21:31:476 (UTC)	|	+[JSONController transToJson:] line 36 $ {
176	|	04:21:31:476 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
177	|	04:21:31:476 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateToken
178	|	04:21:31:477 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 645 $ Navigation ViewControllers at DidBecome end : (
179	|	04:21:31:540 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
180	|	04:21:31:540 (UTC)	|	-[AppDelegate recvTokenInfo:] line 1007 $ Function Called.
181	|	04:21:31:541 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
182	|	04:21:35:784 (UTC)	|	-[SCTViewController sendSCTRequests:] line 637 $ Function Called.
183	|	04:21:35:785 (UTC)	|	+[JSONController transToJson:] line 36 $ {
184	|	04:21:35:786 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
185	|	04:21:35:787 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://old-api./counseling/texttime/ExtraModule/
186	|	04:21:35:988 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
187	|	04:21:35:989 (UTC)	|	-[SCTViewController recvSCTResponse:] line 662 $ Function Called.
188	|	04:21:35:990 (UTC)	|	-[SCTMenuViewController changeStatus:answer:] line 216 $ Function Called.
189	|	04:21:37:450 (UTC)	|	-[SCTViewController popViewAction] line 263 $ Function Called.
190	|	04:21:37:455 (UTC)	|	-[SCTViewController viewWillDisappear:] line 95 $ Function Called.
191	|	04:21:40:125 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
192	|	04:21:40:125 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
193	|	04:21:40:139 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
194	|	04:21:40:139 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
195	|	04:21:40:148 (UTC)	|	-[ChatViewController tableView:cellForRowAtIndexPath:] line 2560 $ -[ChatViewController tableView:cellForRowAtIndexPath:]
```



ID : 675541929

2018/01/23

```
1	|	10:21:05:633 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
2	|	10:21:19:399 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
3	|	10:21:22:929 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
4	|	10:21:22:930 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
5	|	10:21:22:963 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
6	|	10:21:22:963 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
7	|	10:21:22:970 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
8	|	10:21:22:970 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
9	|	10:21:23:073 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
10	|	10:21:23:073 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
11	|	10:21:23:077 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
12	|	10:21:23:079 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
13	|	10:21:23:080 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
14	|	10:21:23:085 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
15	|	10:21:23:086 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
16	|	10:21:23:158 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
17	|	10:21:46:836 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
18	|	10:21:46:837 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
19	|	10:21:46:839 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
20	|	10:21:46:843 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
21	|	10:21:46:845 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
22	|	10:21:46:869 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
23	|	10:21:47:742 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
24	|	10:21:47:743 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
25	|	10:21:47:757 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
26	|	10:21:47:757 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
27	|	10:21:47:759 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
28	|	10:21:47:768 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
29	|	10:22:52:593 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
30	|	10:22:57:339 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
31	|	10:22:57:341 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
32	|	10:22:57:377 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
33	|	10:22:57:378 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
34	|	10:22:57:384 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
35	|	10:22:57:385 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
36	|	10:22:57:456 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
37	|	10:22:57:457 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
38	|	10:22:57:459 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
39	|	10:22:57:462 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
40	|	10:22:57:464 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
41	|	10:22:57:468 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
42	|	10:22:57:532 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
43	|	10:22:57:590 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
44	|	10:22:57:903 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
45	|	10:22:57:906 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
46	|	10:22:57:909 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
47	|	10:22:57:911 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
48	|	10:22:57:913 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
49	|	10:22:57:943 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
50	|	10:22:59:144 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
51	|	10:22:59:145 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
52	|	10:22:59:159 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
53	|	10:22:59:160 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
54	|	10:22:59:161 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
55	|	10:22:59:169 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
56	|	10:23:45:633 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
57	|	10:23:45:635 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
58	|	10:23:45:641 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
59	|	10:23:45:642 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
60	|	10:23:45:644 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
61	|	10:23:45:676 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
62	|	10:23:46:306 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
63	|	10:23:46:322 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
64	|	10:23:46:323 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
65	|	10:23:46:930 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
66	|	10:23:46:946 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
67	|	10:23:46:946 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
68	|	10:24:16:504 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
69	|	10:24:27:165 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
70	|	10:24:27:167 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
71	|	10:24:31:303 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
72	|	10:24:32:953 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
73	|	10:24:32:954 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
74	|	10:24:32:988 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
75	|	10:24:32:989 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
76	|	10:24:32:995 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
77	|	10:24:32:996 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
78	|	10:24:33:064 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
79	|	10:24:33:064 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
80	|	10:24:33:067 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
81	|	10:24:33:070 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
82	|	10:24:33:072 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
83	|	10:24:33:076 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
84	|	10:24:33:140 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
85	|	10:24:33:196 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
86	|	10:24:47:853 (UTC)	|	-[ChatViewController preReportEditBtnTapped:] line 1538 $ Function Called.
87	|	10:24:47:854 (UTC)	|	+[TRHTTPController sendNewHTTPRequest:method:response:] line 16 $ Function Called.
88	|	10:24:47:857 (UTC)	|	+[TRHTTPController sendNewHTTPRequest:method:response:] line 21 $ URL : https://api.trost.co.kr/mypage/pre_report/675541929
89	|	10:24:47:956 (UTC)	|	+[TRHTTPController sendNewHTTPRequest:method:response:]_block_invoke_2 line 55 $ Response :
90	|	10:24:47:961 (UTC)	|	-[CounselInfoHomeViewController settingValuesWithReadData] line 68 $ Function Called.
91	|	10:24:47:975 (UTC)	|	Religion setValue
92	|	10:24:47:995 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
93	|	10:24:47:996 (UTC)	|	-[CounselInfoHomeViewController viewWillAppear:] line 1804 $ Function Called.
94	|	10:24:47:999 (UTC)	|	-[CounselInfoHomeViewController settingValuesWithReloadData:] line 733 $ Function Called.
95	|	10:24:48:618 (UTC)	|	-[ChatViewController viewDidDisappear:] line 478 $ Function Called.
96	|	10:24:48:619 (UTC)	|	-[ChatViewController sendUpdateLastReadNoRequest] line 882 $ Function Called.
97	|	10:24:48:621 (UTC)	|	+[JSONController transToJson:] line 36 $ {
98	|	10:24:48:623 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
99	|	10:24:48:625 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateLastReadNo
100	|	10:24:48:753 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
101	|	10:24:51:888 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
102	|	10:24:51:889 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
103	|	10:24:51:892 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
104	|	10:24:52:462 (UTC)	|	-[CounselInfoHomeViewController viewDidDisappear:] line 1834 $ Function Called.
105	|	10:24:58:704 (UTC)	|	-[ChatViewController backToRootView:] line 921 $ Function Called.
106	|	10:24:58:707 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
107	|	10:24:58:707 (UTC)	|	-[MenuViewController viewWillAppear:] line 149 $ Function Called.
108	|	10:24:58:715 (UTC)	|	-[MenuViewController badgeDrawer] line 1189 $ Function Called.
109	|	10:24:58:716 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
110	|	10:24:58:717 (UTC)	|	-[MenuViewController sendMoreTapReqeusts] line 3397 $ Function Called.
111	|	10:24:58:719 (UTC)	|	-[AppDelegate setIndicatorView] line 765 $ Function Called.
112	|	10:24:58:721 (UTC)	|	+[TRHTTPController sendNewHTTPRequest:method:response:] line 16 $ Function Called.
113	|	10:24:58:723 (UTC)	|	+[TRHTTPController sendNewHTTPRequest:method:response:] line 21 $ URL : https://api.trost.co.kr/mypage/675541929
114	|	10:24:58:850 (UTC)	|	+[TRHTTPController sendNewHTTPRequest:method:response:]_block_invoke_2 line 55 $ Response :
115	|	10:24:58:850 (UTC)	|	-[MenuViewController recvMoreTapResponse:] line 3426 $ Function Called.
116	|	10:24:58:852 (UTC)	|	-[MoreInfoViewController updateInfo:] line 276 $ Function Called.
117	|	10:24:58:854 (UTC)	|	-[AppDelegate removeIndicatorView] line 790 $ Function Called.
118	|	10:24:59:283 (UTC)	|	-[ChatViewController viewDidDisappear:] line 478 $ Function Called.
119	|	10:24:59:283 (UTC)	|	-[ChatViewController sendUpdateLastReadNoRequest] line 882 $ Function Called.
120	|	10:24:59:288 (UTC)	|	+[JSONController transToJson:] line 36 $ {
121	|	10:24:59:289 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
122	|	10:24:59:291 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateLastReadNo
123	|	10:24:59:294 (UTC)	|	[Trost_iOS.SocketIOController removeChatInfo()]
124	|	10:24:59:296 (UTC)	|	[Trost_iOS.SocketIOController addHandlerForCounselList()]
125	|	10:24:59:298 (UTC)	|	-[MenuViewController badgeDrawer] line 1189 $ Function Called.
126	|	10:24:59:299 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
127	|	10:24:59:301 (UTC)	|	-[ClientCounselingViewController refresh] line 395 $ Function Called.
128	|	10:24:59:367 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
129	|	10:25:00:362 (UTC)	|	-[MenuViewController tabBarController:didSelectViewController:] line 519 $ Function Called.
130	|	10:25:00:371 (UTC)	|	-[MenuViewController sendKeywordLoadReqeusts] line 3316 $ Function Called.
131	|	10:25:00:371 (UTC)	|	-[AppDelegate setIndicatorView] line 765 $ Function Called.
132	|	10:25:00:373 (UTC)	|	+[JSONController transToJson:] line 36 $ {
133	|	10:25:00:375 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
134	|	10:25:00:376 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://old-api./user/keyword/
135	|	10:25:00:435 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
136	|	10:25:00:436 (UTC)	|	-[MenuViewController recvKeywordLoadResponse:] line 3342 $ Function Called.
137	|	10:25:00:440 (UTC)	|	-[ClientMatchPartnerView setup] line 100 $ Function Called.
138	|	10:25:00:481 (UTC)	|	-[ClientMatchPartnerView drawRect:] line 170 $ Function Called.
139	|	10:25:00:555 (UTC)	|	-[ClientMatchPartnerView sendMatchPartnerRequests] line 1278 $ Function Called.
140	|	10:25:00:555 (UTC)	|	+[JSONController transToJson:] line 36 $ {
141	|	10:25:00:556 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
142	|	10:25:00:558 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://old-api./counseling/texttime/MatchPartner/
143	|	10:25:00:677 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
144	|	10:25:00:678 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
145	|	10:25:00:703 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
146	|	10:25:00:703 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
147	|	10:25:00:733 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
148	|	10:25:00:738 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
149	|	10:25:00:739 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
150	|	10:25:00:754 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
151	|	10:25:00:754 (UTC)	|	-[ClientMatchPartnerView recvMatchPartnerResponse:] line 1324 $ Function Called.
152	|	10:25:00:755 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
153	|	10:25:00:757 (UTC)	|	-[AppDelegate removeIndicatorView] line 790 $ Function Called.
154	|	10:25:00:854 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
155	|	10:25:00:858 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
156	|	10:25:00:862 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
157	|	10:25:00:862 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
158	|	10:25:00:864 (UTC)	|	-[ClientMatchPartnerView observeValueForKeyPath:ofObject:change:context:] line 1176 $ Function Called.
159	|	10:25:01:169 (UTC)	|	-[MenuViewController tabBarController:didSelectViewController:] line 519 $ Function Called.
160	|	10:25:01:174 (UTC)	|	-[ClientCounselingViewController refresh] line 395 $ Function Called.
161	|	10:25:01:179 (UTC)	|	-[ClientCounselingViewController settingPartnerImgWith:andApplyCell:] line 808 $ Function Called.
162	|	10:25:01:183 (UTC)	|	-[ClientCounselingViewController settingPartnerImgWith:andApplyCell:] line 808 $ Function Called.
163	|	10:25:01:185 (UTC)	|	-[ClientCounselingViewController settingPartnerImgWith:andApplyCell:] line 808 $ Function Called.
164	|	10:25:01:187 (UTC)	|	-[ClientCounselingViewController settingPartnerImgWith:andApplyCell:] line 808 $ Function Called.
165	|	10:25:01:854 (UTC)	|	-[ClientCounselingViewController tableView:didSelectRowAtIndexPath:] line 839 $ Function Called.
166	|	10:25:01:912 (UTC)	|	-[EmojiPlusView initWithEmojiMaker:] line 23 $ Function Called.
167	|	10:25:01:913 (UTC)	|	-[EmojiPlusView setup] line 38 $ Function Called.
168	|	10:25:01:916 (UTC)	|	-[ChatViewController showLoadingViewWithWarnStr:] line 4843 $ Function Called.
169	|	10:25:01:917 (UTC)	|	-[ChatViewController settingSocketState] line 5094 $ Function Called.
170	|	10:25:01:918 (UTC)	|	[Trost_iOS.SocketIOController setup(url:chatRoomInfo:)]
171	|	10:25:01:920 (UTC)	|	[Socket.IO Connect URL : http://node-api.trost.co.kr:8763]
172	|	10:25:01:922 (UTC)	|	[Trost_iOS.SocketIOController addHandler()]
173	|	10:25:01:924 (UTC)	|	[Trost_iOS.SocketIOController sendEnterCounseling()]
174	|	10:25:01:937 (UTC)	|	-[ChatViewController viewDidLoad] line 323 $ ChatVC - Clinet : 675541929 , Partner : sai
175	|	10:25:01:938 (UTC)	|	-[MenuViewController viewWillDisappear:] line 270 $ Function Called.
176	|	10:25:01:939 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
177	|	10:25:01:942 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
178	|	10:25:01:943 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
179	|	10:25:01:967 (UTC)	|	[Trost_iOS.MyInfoView draw]
180	|	10:25:01:971 (UTC)	|	-[EmojiPlusView drawRect:] line 57 $ Function Called.
181	|	10:25:01:977 (UTC)	|	[Trost_iOS.MessageInputView draw]
182	|	10:25:01:998 (UTC)	|	[Trost_iOS.SocketIOController loadMessage(msgArray:)]
183	|	10:25:01:999 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtTop(msgArray:)]
184	|	10:25:02:001 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtBetween(msgArray:)]
185	|	10:25:02:003 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
186	|	10:25:02:005 (UTC)	|	-[ChatViewController endRefreshController] line 5136 $ Function Called.
187	|	10:25:02:006 (UTC)	|	-[ChatViewController tViewScrollToBottomWithRow:] line 5142 $ Function Called.
188	|	10:25:02:129 (UTC)	|	-[ChatViewController stopLoadingIndicator] line 5130 $ Function Called.
189	|	10:25:06:139 (UTC)	|	-[ChatViewController preReportEditBtnTapped:] line 1538 $ Function Called.
190	|	10:25:06:141 (UTC)	|	-[CounselInfoHomeViewController settingValuesWithReloadData:] line 733 $ Function Called.
191	|	10:25:06:169 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
192	|	10:25:06:170 (UTC)	|	-[CounselInfoHomeViewController viewWillAppear:] line 1804 $ Function Called.
193	|	10:25:06:174 (UTC)	|	-[CounselInfoHomeViewController settingValuesWithReloadData:] line 733 $ Function Called.
194	|	10:25:06:757 (UTC)	|	-[ChatViewController viewDidDisappear:] line 478 $ Function Called.
195	|	10:25:15:632 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
196	|	10:25:15:633 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
197	|	10:25:15:636 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
198	|	10:25:16:171 (UTC)	|	-[CounselInfoHomeViewController viewDidDisappear:] line 1834 $ Function Called.
199	|	10:25:20:242 (UTC)	|	[Trost_iOS.SocketIOController sendLoadMessageRequest()]
200	|	10:25:20:267 (UTC)	|	[Trost_iOS.SocketIOController loadMessage(msgArray:)]
201	|	10:25:20:268 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtTop(msgArray:)]
202	|	10:25:20:269 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtBetween(msgArray:)]
203	|	10:25:20:273 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
204	|	10:25:20:282 (UTC)	|	-[ChatViewController endRefreshController] line 5136 $ Function Called.
205	|	10:25:20:282 (UTC)	|	-[ChatViewController tViewScrollToTopWithRow:] line 5152 $ Function Called.
206	|	10:25:20:403 (UTC)	|	-[ChatViewController stopLoadingIndicator] line 5130 $ Function Called.
207	|	10:25:23:102 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
208	|	10:25:23:103 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
209	|	10:25:23:106 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
210	|	10:25:23:109 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
211	|	10:25:23:111 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
212	|	10:25:23:162 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
213	|	10:25:24:294 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
214	|	10:25:24:294 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
215	|	10:25:24:297 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
216	|	10:25:24:314 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
217	|	10:25:24:315 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
218	|	10:25:24:318 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
219	|	10:26:18:555 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
220	|	10:26:21:558 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
221	|	10:26:21:559 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
222	|	10:26:33:196 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
223	|	10:26:58:280 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
224	|	10:26:58:281 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
225	|	10:27:05:762 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
226	|	10:27:57:143 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
227	|	10:27:57:145 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
228	|	10:27:57:811 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
229	|	10:28:06:566 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
230	|	10:28:06:568 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
231	|	10:28:10:598 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
232	|	10:28:15:431 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
233	|	10:28:15:433 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
234	|	10:28:17:052 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
235	|	10:29:25:056 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
236	|	10:29:25:057 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
237	|	10:29:27:181 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
238	|	10:29:32:599 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
239	|	10:29:32:600 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
240	|	10:29:38:360 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
241	|	10:29:44:128 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
242	|	10:29:44:129 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
243	|	10:29:46:863 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
244	|	10:29:55:985 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
245	|	10:29:55:986 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
246	|	10:30:01:671 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
247	|	10:30:01:673 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
248	|	10:30:01:720 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
249	|	10:30:01:720 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
250	|	10:30:01:784 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
251	|	10:30:01:784 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
252	|	10:30:01:864 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
253	|	10:30:01:864 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
254	|	10:30:01:867 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
255	|	10:30:01:870 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
256	|	10:30:01:871 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
257	|	10:30:01:875 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
258	|	10:30:01:946 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
259	|	10:30:02:012 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
260	|	10:30:07:335 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
261	|	10:30:07:336 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
262	|	10:32:01:250 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
263	|	10:32:01:252 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
264	|	10:32:01:256 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
265	|	10:32:01:258 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
266	|	10:32:01:260 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
267	|	10:32:01:284 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
268	|	10:32:02:235 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
269	|	10:32:02:235 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
270	|	10:32:02:255 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
271	|	10:32:02:256 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
272	|	10:32:02:258 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
273	|	10:32:02:261 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
274	|	10:32:07:656 (UTC)	|	-[AppDelegate applicationWillResignActive:] line 2682 $ Function Called.
275	|	10:32:07:657 (UTC)	|	-[AppDelegate applicationWillResignActive:] line 2684 $ Before function proceed ViewControllers : (
276	|	10:32:07:672 (UTC)	|	-[AppDelegate applicationDidEnterBackground:] line 651 $ Function Called.
277	|	10:32:07:672 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
278	|	10:32:07:675 (UTC)	|	-[ChatViewController viewDidDisappear:] line 478 $ Function Called.
279	|	10:32:07:675 (UTC)	|	-[ChatViewController sendUpdateLastReadNoRequest] line 882 $ Function Called.
280	|	10:32:07:678 (UTC)	|	+[JSONController transToJson:] line 36 $ {
281	|	10:32:07:680 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
282	|	10:32:07:682 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateLastReadNo
283	|	10:32:07:920 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
284	|	10:32:49:233 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 583 $ Function Called.
285	|	10:32:49:234 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 584 $ Navigation ViewControllers at DidBecome start : (
286	|	10:32:49:235 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
287	|	10:32:49:242 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
288	|	10:32:49:242 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
289	|	10:32:49:243 (UTC)	|	-[AppDelegate sendTokenInfo] line 971 $ Function Called.
290	|	10:32:49:248 (UTC)	|	+[JSONController transToJson:] line 36 $ {
291	|	10:32:49:248 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2760 $ Function Called.
292	|	10:32:49:250 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:] line 2775 $ URL : https://:1242/updateToken
293	|	10:32:49:252 (UTC)	|	-[AppDelegate applicationDidBecomeActive:] line 645 $ Navigation ViewControllers at DidBecome end : (
294	|	10:32:49:532 (UTC)	|	-[AppDelegate sendHTTPRequest:withJson:response:]_block_invoke_2 line 2804 $ Response :
295	|	10:32:49:532 (UTC)	|	-[AppDelegate recvTokenInfo:] line 1007 $ Function Called.
296	|	10:32:49:533 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
297	|	10:32:49:545 (UTC)	|	-[MenuViewController settingFinishRoomNumber:] line 2057 $ Function Called.
298	|	10:32:49:549 (UTC)	|	-[MenuViewController sendCounselorRequests:] line 2675 $ Function Called.
299	|	10:32:49:739 (UTC)	|	Socket loadCounselingListOfClient (null)
300	|	10:32:49:740 (UTC)	|	-[MenuViewController recvCounselingListInfoForClientWithCounselingListInfo:] line 2064 $ Function Called.
301	|	10:32:49:744 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2074 $ Function Called.
302	|	10:32:49:745 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
303	|	10:32:49:749 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
304	|	10:32:49:750 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
305	|	10:32:49:752 (UTC)	|	-[MenuViewController saveClientInfo:roomNo:] line 2099 $ Already Enrolled chatRoomInfo.
306	|	10:32:49:753 (UTC)	|	-[AppDelegate removeIndicatorView] line 790 $ Function Called.
307	|	10:32:49:755 (UTC)	|	-[ClientCounselingViewController updateInfo:] line 507 $ Function Called.
308	|	10:32:49:758 (UTC)	|	-[MenuViewController badgeDrawer] line 1189 $ Function Called.
309	|	10:32:49:759 (UTC)	|	-[MenuViewController list_noChanged] line 929 $ Function Called.
310	|	10:32:49:874 (UTC)	|	-[EmojiPlusView initWithEmojiMaker:] line 23 $ Function Called.
311	|	10:32:49:875 (UTC)	|	-[EmojiPlusView setup] line 38 $ Function Called.
312	|	10:32:49:979 (UTC)	|	-[ChatViewController showLoadingViewWithWarnStr:] line 4843 $ Function Called.
313	|	10:32:49:979 (UTC)	|	-[ChatViewController settingSocketState] line 5094 $ Function Called.
314	|	10:32:49:981 (UTC)	|	[Trost_iOS.SocketIOController setup(url:chatRoomInfo:)]
315	|	10:32:49:983 (UTC)	|	[Socket.IO Connect URL : http://node-api.trost.co.kr:8763]
316	|	10:32:49:985 (UTC)	|	[Trost_iOS.SocketIOController addHandler()]
317	|	10:32:49:987 (UTC)	|	[Trost_iOS.SocketIOController sendEnterCounseling()]
318	|	10:32:49:989 (UTC)	|	-[ChatViewController showLoadingViewWithWarnStr:] line 4843 $ Function Called.
319	|	10:32:49:996 (UTC)	|	-[ChatViewController viewDidLoad] line 323 $ ChatVC - Clinet : 675541929 , Partner : sai
320	|	10:32:49:997 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
321	|	10:32:49:998 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
322	|	10:32:50:000 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
323	|	10:32:50:002 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
324	|	10:32:50:059 (UTC)	|	[Trost_iOS.MyInfoView draw]
325	|	10:32:50:064 (UTC)	|	-[EmojiPlusView drawRect:] line 57 $ Function Called.
326	|	10:32:50:318 (UTC)	|	[Trost_iOS.MessageInputView draw]
327	|	10:32:50:659 (UTC)	|	[Trost_iOS.SocketIOController loadMessage(msgArray:)]
328	|	10:32:50:659 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtTop(msgArray:)]
329	|	10:32:50:661 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtBetween(msgArray:)]
330	|	10:32:50:663 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
331	|	10:32:50:665 (UTC)	|	-[ChatViewController endRefreshController] line 5136 $ Function Called.
332	|	10:32:50:667 (UTC)	|	-[ChatViewController tViewScrollToBottomWithRow:] line 5142 $ Function Called.
333	|	10:32:50:774 (UTC)	|	-[ChatViewController stopLoadingIndicator] line 5130 $ Function Called.
334	|	10:32:50:775 (UTC)	|	[Trost_iOS.SocketIOController loadMessage(msgArray:)]
335	|	10:32:50:777 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtTop(msgArray:)]
336	|	10:32:50:779 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtBetween(msgArray:)]
337	|	10:32:50:781 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
338	|	10:32:50:783 (UTC)	|	-[ChatViewController endRefreshController] line 5136 $ Function Called.
339	|	10:32:50:785 (UTC)	|	-[ChatViewController tViewScrollToTopWithRow:] line 5152 $ Function Called.
340	|	10:32:50:931 (UTC)	|	-[ChatViewController stopLoadingIndicator] line 5130 $ Function Called.
341	|	10:32:51:159 (UTC)	|	-[ChatViewController viewDidDisappear:] line 478 $ Function Called.
342	|	10:33:00:232 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
343	|	10:33:21:327 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
344	|	10:33:21:328 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
345	|	10:33:21:331 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
346	|	10:33:21:334 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
347	|	10:33:21:336 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
348	|	10:33:21:365 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
349	|	10:33:21:365 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
350	|	10:33:21:367 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
351	|	10:33:21:369 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
352	|	10:33:21:376 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
353	|	10:33:22:787 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
354	|	10:33:22:788 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
355	|	10:33:22:808 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
356	|	10:33:22:808 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
357	|	10:33:22:810 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
358	|	10:33:22:813 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
359	|	10:33:25:102 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
360	|	10:33:25:106 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
361	|	10:33:29:252 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
362	|	10:33:41:410 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
363	|	10:33:41:412 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
364	|	10:33:46:798 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
365	|	10:33:59:775 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
366	|	10:33:59:777 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
367	|	10:34:03:716 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
368	|	10:34:13:088 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
369	|	10:34:13:091 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
370	|	10:34:13:127 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
371	|	10:34:13:128 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
372	|	10:34:13:137 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
373	|	10:34:13:137 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
374	|	10:34:13:273 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
375	|	10:34:13:274 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
376	|	10:34:13:276 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
377	|	10:34:13:279 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
378	|	10:34:13:279 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
379	|	10:34:13:288 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
380	|	10:34:13:288 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
381	|	10:34:13:290 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
382	|	10:34:13:292 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
383	|	10:34:13:294 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
384	|	10:34:13:408 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
385	|	10:34:13:481 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
386	|	10:34:13:548 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
387	|	10:34:15:762 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
388	|	10:34:15:762 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
389	|	10:34:17:767 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
390	|	10:34:17:768 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
391	|	10:34:18:573 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
392	|	10:34:18:574 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
393	|	10:34:18:578 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
394	|	10:34:18:580 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
395	|	10:34:18:582 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
396	|	10:34:18:621 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
397	|	10:34:18:622 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
398	|	10:34:18:624 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
399	|	10:34:18:626 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
400	|	10:34:18:628 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
401	|	10:34:19:933 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
402	|	10:34:19:933 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
403	|	10:34:19:942 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
404	|	10:34:19:942 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
405	|	10:34:19:951 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
406	|	10:34:19:960 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
407	|	10:34:20:385 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
408	|	10:34:20:385 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
409	|	10:34:25:679 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
410	|	10:34:49:253 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
411	|	10:34:49:255 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
412	|	10:34:49:425 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
413	|	10:35:03:730 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
414	|	10:35:03:731 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
415	|	10:35:04:442 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
416	|	10:35:07:677 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
417	|	10:35:07:679 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
418	|	10:35:07:697 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
419	|	10:35:07:698 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
420	|	10:35:07:703 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
421	|	10:35:07:704 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
422	|	10:35:07:799 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
423	|	10:35:07:799 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
424	|	10:35:07:802 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
425	|	10:35:07:804 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
426	|	10:35:07:806 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
427	|	10:35:07:813 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
428	|	10:35:07:813 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
429	|	10:35:07:814 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
430	|	10:35:07:816 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
431	|	10:35:07:818 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
432	|	10:35:07:821 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
433	|	10:35:07:878 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
434	|	10:35:07:939 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
435	|	10:35:29:202 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
436	|	10:35:29:204 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
437	|	10:35:29:207 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
438	|	10:35:29:210 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
439	|	10:35:29:212 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
440	|	10:35:29:244 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
441	|	10:35:29:244 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
442	|	10:35:29:246 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
443	|	10:35:29:248 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
444	|	10:35:29:250 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
445	|	10:35:30:318 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
446	|	10:35:30:318 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
447	|	10:35:30:334 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
448	|	10:35:30:334 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
449	|	10:35:30:338 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
450	|	10:35:30:349 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
451	|	10:35:37:388 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
452	|	10:35:41:312 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
453	|	10:35:41:314 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
454	|	10:35:42:456 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
455	|	10:35:56:057 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
456	|	10:35:56:058 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
457	|	10:35:56:454 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
458	|	10:35:59:168 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
459	|	10:35:59:170 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
460	|	10:35:59:208 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
461	|	10:35:59:208 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
462	|	10:35:59:215 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
463	|	10:35:59:216 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
464	|	10:35:59:318 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
465	|	10:35:59:318 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
466	|	10:35:59:321 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
467	|	10:35:59:324 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
468	|	10:35:59:326 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
469	|	10:35:59:331 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
470	|	10:35:59:331 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
471	|	10:35:59:333 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
472	|	10:35:59:335 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
473	|	10:35:59:336 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
474	|	10:35:59:409 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
475	|	10:35:59:469 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
476	|	10:35:59:527 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
477	|	10:36:10:522 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
478	|	10:36:44:177 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
479	|	10:36:44:178 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
480	|	10:36:46:980 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
481	|	10:36:50:625 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
482	|	10:36:50:627 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
483	|	10:36:51:934 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
484	|	10:37:00:824 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
485	|	10:37:00:826 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
486	|	10:37:14:951 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
487	|	10:37:22:702 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
488	|	10:37:22:703 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
489	|	10:37:23:919 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
490	|	10:37:30:673 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
491	|	10:37:30:675 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
492	|	10:37:33:832 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
493	|	10:37:35:501 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
494	|	10:37:35:502 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
495	|	10:37:35:504 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
496	|	10:37:35:507 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
497	|	10:37:35:509 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
498	|	10:37:35:528 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
499	|	10:37:35:529 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
500	|	10:37:35:530 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
501	|	10:37:35:532 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
502	|	10:37:35:534 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
503	|	10:37:36:661 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
504	|	10:37:36:662 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
505	|	10:37:36:696 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1734 $ Function Called.
506	|	10:37:36:697 (UTC)	|	-[AppDelegate userNotificationCenter:willPresentNotification:withCompletionHandler:] line 1740 $ Response :
507	|	10:37:36:698 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
508	|	10:37:36:709 (UTC)	|	-[AppDelegate application:didReceiveRemoteNotification:fetchCompletionHandler:] line 1505 $ Function Called.
509	|	10:37:39:261 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
510	|	10:37:39:269 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
511	|	10:37:40:520 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
512	|	10:37:45:487 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
513	|	10:37:45:488 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
514	|	10:37:58:250 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
515	|	10:38:16:620 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
516	|	10:38:16:621 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
517	|	10:38:16:676 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
518	|	10:40:54:729 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
519	|	10:40:54:730 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
520	|	10:41:00:554 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
521	|	10:41:08:743 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
522	|	10:41:08:746 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
523	|	10:41:10:333 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
524	|	10:41:16:782 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
525	|	10:41:16:784 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
526	|	10:41:18:696 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
527	|	10:41:25:376 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
528	|	10:41:25:378 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
529	|	10:41:27:493 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
530	|	10:41:38:911 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
531	|	10:41:38:913 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
532	|	10:41:40:194 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
533	|	10:42:22:834 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
534	|	10:42:22:836 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
535	|	10:42:22:869 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
536	|	10:42:22:870 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
537	|	10:42:22:961 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
538	|	10:42:22:961 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
539	|	10:42:22:994 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
540	|	10:42:22:995 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
541	|	10:42:22:997 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
542	|	10:42:22:999 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
543	|	10:42:23:000 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
544	|	10:42:23:006 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
545	|	10:42:23:006 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
546	|	10:42:23:008 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
547	|	10:42:23:009 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
548	|	10:42:23:011 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
549	|	10:42:23:088 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
550	|	10:42:23:169 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
551	|	10:42:23:237 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
552	|	10:42:25:422 (UTC)	|	[Trost_iOS.SocketIOController sendMessageTypingRequests()]
553	|	10:42:44:637 (UTC)	|	[Trost_iOS.MessageInputView sendBtnTapped(btn:)]
554	|	10:42:44:638 (UTC)	|	-[ChatViewController sendBtnTappedWithBtn:msg:] line 5013 $ Function Called.
555	|	10:42:44:661 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
556	|	10:42:44:661 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
557	|	10:42:44:670 (UTC)	|	-[ChatViewController sendMessageStopTypingEmit] line 5235 $ Function Called.
558	|	10:42:44:671 (UTC)	|	[Trost_iOS.SocketIOController sendMessageStopTypingRequests()]
559	|	10:42:44:755 (UTC)	|	Socket loadNewMessage in CounselList handler (null)
560	|	10:42:44:756 (UTC)	|	-[MenuViewController recvNewMessageForListForClientWithMessage:] line 2385 $ Function Called.
561	|	10:42:44:758 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
562	|	10:42:44:761 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
563	|	10:42:44:763 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
564	|	10:42:44:770 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
565	|	10:42:44:770 (UTC)	|	[Trost_iOS.SocketIOController recvNewMessage(data:)]
566	|	10:42:44:772 (UTC)	|	[Trost_iOS.SocketIOController insertDateCellAtNewMsgSide(msgArray:searchBound:)]
567	|	10:42:44:774 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
568	|	10:42:44:776 (UTC)	|	-[ChatViewController bottomMsgManageWithMessage:] line 5201 $ Function Called.
569	|	10:42:44:875 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
570	|	10:42:44:954 (UTC)	|	-[ChatViewController tViewReloadDataWithMessages:] line 5172 $ Function Called.
571	|	10:42:45:023 (UTC)	|	[Trost_iOS.SocketIOController sendMessageRequests(msg:)]
572	|	10:43:12:133 (UTC)	|	-[ChatViewController viewWillDisappear:] line 468 $ Function Called.
573	|	10:43:12:135 (UTC)	|	-[ChatViewController viewWillAppear:] line 329 $ Function Called.
574	|	10:43:12:148 (UTC)	|	-[ChatViewController setBadgeNumber] line 897 $ Function Called.
575	|	10:43:12:149 (UTC)	|	[Trost_iOS.SocketIOController reconnectSocket()]
```

