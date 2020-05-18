@client.has_permissions(manage_messages =True) # makes sure user has permission Manage Messages
@client.command()
async def clear(ctx, ammount=1): # !clear 5   By Default it clears 1 message
    await ctx.channel.purge(limit=ammount+1) #Takes the ammount from above, deletes that many messages + 1 extra for the command itself
    await ctx.send(f":broom: Cleared **{ammount}** messages!", delete_after=3) # Saysits cleared and how many its cleared
