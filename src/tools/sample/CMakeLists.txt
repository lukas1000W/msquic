# Copyright (c) Microsoft Corporation.
# Licensed under the MIT License.

add_quic_tool(fileserver msquic_file_server.c)
add_quic_tool(quicsample sample.c)
quic_tool_warnings(quicsample)