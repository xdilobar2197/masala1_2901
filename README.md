# masala1_2901
# matn = ('salom python')
# print(matn.title())

# a = [1, 2, 3, 4]
# b = [5, 6, 7, 8]
# natija = a + b
# print(natija)

# def noyob_harflar(matn):
#     natija = ""
#     for harf in matn:
#         if harf not in natija:
#             natija += harf
#     return natija

# def ajratish(royxat):
#     juft = []
#     toq = []
#
#     for i in range(len(royxat)):
#         if i % 2 == 0:
#             juft.append(royxat[i])
#         else:
#             toq.append(royxat[i])
#
#     return juft, toq
#
# sonlar = [10, 20, 30, 40, 50, 60]
# juft, toq = ajratish(sonlar)
#
# print("Juft indekslilar:", juft)
# print("Toq indekslilar:", toq)

#
# def guruhla(royxat):
#     if not royxat:
#         return []
#
#     natija = []
#     joriy = royxat[0]
#     sanoq = 1
#
#     for i in range(1, len(royxat)):
#         if royxat[i] == joriy:
#             sanoq += 1
#         else:
#             natija.append((joriy, sanoq))
#             joriy = royxat[i]
#             sanoq = 1
#
#     # oxirgi guruhni qo‘shamiz
#     natija.append((joriy, sanoq))
#     return natija
#
# royxat = [1, 1, 2, 2, 2, 3, 1]
# print(guruhla(royxat))



#
# def farq_top(royxat):
#     if len(royxat) <= 2:
#         return None
#
#     max_q = max(royxat)
#     min_q = min(royxat)
#
#     yangi = royxat.copy()
#     yangi.remove(max_q)
#     yangi.remove(min_q)
#
#     return max(yangi) - min(yangi)
#
#
#
# sonlar = [1, 2, 3, 4, 5]
# print(farq_top(sonlar))
