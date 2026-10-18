FROM almalinux:9

#CMD can be ovveridden
#CMD ["ping", "google.com"]

# the below command, it will not ovveride, ut i will append, if we tried ping other than google.
#ENTRYPOINT ["ping", "google.com"]

RUN dnf install git -y
RUN useradd karthikeya

#Giving access to karthikeya user, [root ll cause issue, root ki access ivvakudadu, beacause it ll block the other containers storage also.]
USER karthikeya
# ekkada, while doing docker run entry:v1 -> emi ika pothe google ni run chestundi, other than google ni isthe like docker run entry:v1 instagram.com , instagram ni ping avtundi
CMD ["google.com"]
ENTRYPOINT ["ping"]
