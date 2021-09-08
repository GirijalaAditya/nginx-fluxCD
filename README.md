# nginx-fluxCD

fluxctl install \
--git-user=${GHUSER} \
--git-email=${GHUSER}@users.noreply.github.com \
--git-url=git@github.com:${GHUSER}/nginx-fluxCD \
--git-branch=main \
--git-path=kubernetes \
--namespace=springboot | kubectl apply -f -
