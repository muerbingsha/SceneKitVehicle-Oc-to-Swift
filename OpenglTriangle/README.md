

some details:
1) index type must be GLuint, Int will orrcur error.
2) before you connect with shader uniform(glGetUniformLocation, glUniform3f), you must designate program, that is glUseProgram. Or opengl don't know which program to search.

http://www.jobyme88.com is my personal blog.
http://www.boygirl88.com is my online toy shop, if you have cute babies, you may be interested. We provide many wonderful and economic toys. Only China is availble for ship.
