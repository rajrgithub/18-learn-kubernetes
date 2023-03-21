FROM      dokken/centos-8
ENTRYPOINT ["ping", "-c", "3"]
CMD [ "google.com" ]

# ENTRYPOINT is a default command
# CMD is an argument to ENTRYPOINT

# docker build test entcmd

# ping google.com 3 times
# docker run <%imageid%>

# ping yahoo.com 3 times i.e., value in cmd can be overridden
# docker run <%imageid%> yahoo.com

# ENTRYPOINT cannot be overridden

# ENTRYPOINT can be overridden as below
# docker run --entrypoint bash -it <%imageid%>
